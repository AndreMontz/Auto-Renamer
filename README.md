# Auto-Renamer
Auto Renamer is a productivity utility that organizes images and GIFs in real-time. Operating in the background, it adds sequential numbering to original filenames as they enter a folder. It features independent directory counters, a recent history log, custom folder groups, and starts automatically with Windows.

This is a background utility for Windows that monitors a selected folder and automatically renames any new image added to it. The program adds a sequential number to the beginning of the original filename (e.g., image.png becomes 1-image.png).

Ideal for those who download many images and need to keep them organized chronologically by arrival time, without losing the original filename.

Features
Invisible Operation: Runs silently in the system tray (near the Windows clock). No open windows to interrupt your workflow.

Auto-Start: Starts with Windows so you don't have to remember to open it every day.

Multiple Counters: The program remembers where it left off in each folder independently.

History (Recent): Saves the last 10 used folders for quick switching.

Organizational Groups: Allows you to save your favorite folders into custom categories for easy future access.

Portable (Standalone): Does not require Python or extra libraries to be installed. Just run the .exe.

How to Use
Place the auto-renamer.exe file in a folder of your choice.

Double-click the file to open it.

Look at the Windows system tray (bottom right corner, near the clock) and look for a green icon.

Right-click the icon to open the menu.

Select Select Folder and choose the folder where you will download or save your images.

Done! From now on, any image saved in that folder will be automatically numbered in the order it arrives.

Understanding the Menu
Right-clicking the icon will display the following options:

Folder in use / Next number: Shows the current status so you know where images are being routed and what the next file number will be.

Select Folder: Opens the file explorer so you can change the monitoring destination.

Reset Counter: Resets the current folder's count back to number 1.

Recent: A quick shortcut to return to folders you've used recently. Includes an option to clear this history.

Groups:

Use Save Folder to a Group to create a category (e.g., "Art References", "Memes") and pin the current folder there.

You can access saved folders, rename groups, or delete them through the submenus.

Exit: Closes the program completely.

Technical Notes
Supported Extensions: The program automatically recognizes and renames files with the following extensions: .png, .jpg, .jpeg, .gif, .bmp, .webp, and .tiff.

Configuration File: When run for the first time, the program will create a file named config_renamer.json in the same directory as the .exe. This file stores your counters, history, and groups. Do not delete this file, otherwise, the program will lose track of its numbering progress.

Tip: If you want to temporarily pause the program without closing it, simply create an empty temporary folder and select it in the program, or just click Exit and reopen it later.
