# T3 Raspberry Pi Image

## Key Features:
- Custom Wallpaper
- Custom Splash Screen
- Chrome Shortcuts to Relevant Websites
- Added all NodeRed Nodes that curriculum uses
- Added Applications:
  - Scratch3
  - PiShrink
  - NodeRed + npm
  - Thonny
  - VLC Media Player
  - RPi Imager

## Install Set Up:
1. Start with fresh install of RPiOS
2. Plug into RPi
3. Let first boot go through install sequence
4. Keep the hostname as “raspberrypi” and keep password as “raspberry”

## Change Wallpaper:
1. Go to the start menu and click Preferences>Appearance Settings
2. Click on “Picture” and select your desired wallpaper image
3. You can also mess around with the theme colors as well but that isn't necessary.

## Import Necessary Programs and applications:
1. You can find the script I wrote to auto install everything here at: 
   https://github.com/ItalianSquirel/T3-RPi-Image-Script/
2. For an in-depth list of everything going on please look at the GitHub Link listed.

## Set a home page on Chromium:
1. Open Chromium by clicking on the icon in the taskbar or by running the command chromium-browser in the terminal.
2. Click on the three dots in the top-right corner of the window to open the menu.
3. Click on "Settings" in the menu to open the settings page.
4. In the "Appearance" section, toggle on the option "Show home button".
5. In the "On startup" section, select the option "Open a specific page or set of pages".
6. Click on "Add a new page".
7. In the dialog box that appears, enter the URL for the page you want to set as your homepage and click "Add".
8. You can also add additional pages to open on startup by clicking on "Add another page" and repeating the previous step.
9. Close the settings page by clicking the "X" button in the top-right corner of the window.
10. Now, when you open a new tab or start Chromium, it will automatically open the home page that you set.

## Add to the bookmark bar on Chromium:
1. Open Chromium by clicking on the icon in the taskbar or by running the command chromium-browser in the terminal.
2. Navigate to the website you want to bookmark.
3. Click on the star icon in the right side of the address bar.
4. In the dialog box that appears, select "Bookmark bar" from the "Folder" dropdown menu.
5. Click on "Done" to save the bookmark.
6. The bookmark will now appear in the bookmark bar at the top of the window.
7. You can also drag and drop bookmarks from the bookmarks menu to the bookmark bar to add them, or right-click on a bookmark and select "Edit" to change the bookmark's properties, including its location in the bookmark bar.

## Clean up and Wrap Up:
1. Open the terminal on your Raspberry Pi.
2. Type the following command and press Enter: `history -c`
3. This will clear your terminal history.
4. To confirm that your terminal history has been cleared, type the following command and press Enter: `history`
5. This should display an empty list, indicating that your terminal history has been erased.
6. Note that this only clears the history for the current user. If there are other users who have used the terminal on your Raspberry Pi, their terminal histories will still be stored. If you want to erase the history for all users, you may need to repeat these steps for each user account
