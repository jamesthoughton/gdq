# GDQ Member Checker
Currently this uses the Chrome driver (headless doesn't work yet) to login to the GDQ website to check the number of members that have registered.
The script will ask you for your username and password, but you can also provide them in the environment to avoid prompts.

Every 5 seconds the script will check the number, and it will produce a system bell sound if the number it finds is less than the specified limit (default 1850).