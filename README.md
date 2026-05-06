# Auto-Renamer

Auto-Renamer is a productivity utility that organizes images and GIFs in real-time. Operating in the background, it adds sequential numbering to original filenames as they enter a folder. 

Ideal for those who download many images and need to keep them organized chronologically by arrival time, without losing the original filename (e.g., `image.png` becomes `1-image.png`).

---

## Features

* **Invisible Operation:** Runs silently in the Windows system tray. No open windows to interrupt your workflow.
* **Auto-Start:** Starts automatically with Windows so you don't have to remember to open it every day.
* **Multiple Counters:** The program has independent memory, remembering exactly what number it left off at in each different directory.
* **History (Recent):** Saves the last 10 used folders so you can quickly switch between them.
* **Organizational Groups:** Allows you to save and categorize your favorite folders into custom groups for easy future access.
* **Portable (Standalone):** Does not require Python or extra libraries to be installed. Just run the `.exe` file.

---

## How to Use

1. Place the `auto-renamer.exe` file in a folder of your choice.
2. Double-click the file to run it.
3. Look at the Windows system tray (bottom right corner, near the clock) and look for a green icon with the letter "R".
4. Right-click the icon to open the menu.
5. Select the **Select Folder** option and choose the folder where you will download or save your images.
6. Done! From now on, any image saved in that folder will be automatically numbered in the order it arrives.

---

## Understanding the Menu

Right-clicking the program icon gives you access to the following options:

* **Folder in use / Next number:** Shows the current status so you know which folder images are being routed to and what the next applied number will be.
* **Select Folder:** Opens the file explorer so you can change the folder being monitored.
* **Reset Counter:** Resets the count of the current folder, making the next image receive the number 1 again.
* **Recent:** A shortcut to quickly access the history of used folders. Includes an option to clear this history.
* **Groups:** 
    * Use the **Save Folder to a Group** option to create categories (e.g., "References", "Memes") and pin the current folder to them.
    * Through the submenus, you can quickly access saved folders, as well as rename or delete groups.
* **Language:** Allows you to switch the program's language (English/Português).
* **Exit:** Closes the program completely.

---

## Technical Notes

* **Supported Extensions:** The program automatically recognizes and renames files with the following extensions: `.png`, `.jpg`, `.jpeg`, `.gif`, `.bmp`, `.webp`, and `.tiff`.
* **Configuration File:** When run for the first time, the program will automatically create a file named `config_renamer.json` in the same directory where `auto-renamer.exe` is located. This file stores your counters, folder history, groups, and language preference. **Do not delete this file**, or the program will lose all saved numbering progress.

> **Usage Tip:** If you want to temporarily pause the program's monitoring without having to close it, simply create an empty folder anywhere, select it using the **Select Folder** button, and leave it inactive. Alternatively, click **Exit** and open the program again only when you need it.
