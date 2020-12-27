# MacScreenTimeLapse
An Applescript which records timelapse of your screen, ready for Quicktime to turn into a movie.

##Installation
1. Let's show the Applescript in the menu bar. Open Script Editor and go to Preferences. Select "Show Script in Menu Bar".
A script icon will appear in the Menu Bar.
1. Click it and choose Open Scripts Folder->Open User Scripts Folder.
1. Copy this script (Timelapse Screenshots.scpt) to this folder.


##Usage
1. Optionally, create a folder called "Timelapse Screenshots" on the Desktop. All runs will be in folders under this folder.
1. Run the script. Personally I have Apple Script added to my top menu bar, so that I can access it quickly. Also, when this is enabled you can see a turning gear icon when the script is running. See instructions above for enabling this.
1. Enter the number of frames per minute. I find 120 is a good number, but if you want to capture less, use a smaller number. 120 frames per minute is 2 FPS and played back at 60fps is 2 seconds long.
1. When you're done, stop the script. If you ran it from the top menu bar, click the spinning gear and click the (x). In this dialog you'll see how many screenshots it has saved. The max my iMac will do is 4 FPS.
1. Once stopped, you'll have a folder of screenshots with a sequential filename. Quicktime can import these natively.
1. Open Quicktime, go to File->Open Image Sequence and choose the folder made by the script, inside the folder you chose. Note the folders use the time and date to keep them straight.
1. Save this movie as desired from Quicktime.

Any issues, raise one here.

