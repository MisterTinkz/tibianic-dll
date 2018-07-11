

How To Compile On Windows With Dev C++

Open the the DEV File
ALT + P to open Project Options, or Project -> Project Options from the menu
Then Directories -> Include Directories, and replace ALL the paths to where the source is on your computer
CTRL + F and find in all files: tibria.com and replace them with your IP
Always clean before compiling: Execute -> clean then Execute -> compile
Drag the .dll to your client/game folder




Implement the auto updater

Make a directory called update inside your web server folder. Usually: Linux: /var/www/ or /var/www/html/, and Windows (xampp): C:\xampp\htdocs\
Copy the versions.php to the newly made directory

Not Required:

Not all values are changed in the DLL source, some values require client hex-editing. For this you need: XVI32
You can also change the .dll name by going to Build Options -> Override output filename (If you do this step, you also have to hex edit the client to match the right .dll path)

You're all set.
