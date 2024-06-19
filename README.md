# Make-Windows-Incredible
In this guide, I will help you make your windows install better, this includes the following:
+ ✨This is a guide which will help you make your windows pc much more **secure** and **private** by disabling most of the Telemetry.
+ Plus this guide will aslo make your windows install look way more **beautiful** using Catppuccin theme for most things.
+ Installing some really useful programs.
> [!WARNING]
> This is going to be a long process and will take good amount of hard work.


## Screenshots

## Making Windows more Private
This is gonna include setting up a **SECURE DNS**, **HARDENING FIREFOX**, **REMOVING MOST OF THE TELEMETRY** and some more tips.
So lets get started.

### Installing and hardening firefox
<details close>
<summary>Follow this</summary>
<br>
Install firefox from (https://www.mozilla.org/en-US/firefox/)
  
#### **You can follow this [youtube video](https://www.youtube.com/watch?v=Fr8UFJzpNls&t=490s) for hardening firefox or just follow the following steps.**
  
#### Steps for hardening:
  
1. Changing some basic settings in **settings>home**

> Set homepage and new window to **blank page** (do the same for new tabs)

> Disable: Shortcuts

> Disable: recommended stories

> Disable recent activity

2. Changing settings in **settings>privacy and security**

> Change the tracking protection to Strict

> Enable: Tell websites not to sell or share my data

> Enable: Send websites a “Do Not Track” request

> Go under Firefox Data Collection and Use and disable everything

> Go under HTTPS-Only Mode and Enable: Enable HTTPS-Only Mode in all windows

3. Install extentions

> Ublock origin(for blocking adds)

> Firefox Color(needed later for customizing firefox)

4. Install a user.js file

Go to [Betterfox](https://github.com/yokoffing/Betterfox) and click on **raw** in the right hand side and copy everything.

**Search** `about:profiles` in the address bar of firefox

Under root directory click `Open Directory` or go to `C:\Users\SUJU\AppData\Roaming\Mozilla\Firefox\Profiles\PROFILENAME` in your file manager

Create a file called **user.js** in the onpened directory and paste all of the raw file there and save it.

Now restart firefox and its hardened. Good job!

</details>

## Making Windows beautiful
Time to make everything catppuccin theme.

### Installing Startallback and configuring it
<details close>
<summary>Follow this</summary>
<br>
Steps:

You can follow this [video](https://www.youtube.com/watch?v=kvpZx_SP2SM&list=PLGWgbaPiQ4hp4mYdaoVYnNZzzEym93d0t&index=5) or follow the following steps
  
1. Install startallback from [here](https://startallback.com/)

2. Download this [file](https://github.com/notsuju/Make-Windows-Incredible/blob/main/Catppuccin-theme/Startallback/Catppuccin%20SAB.msstyles)

3. Go to `C:\Program Files\StartAllBack\Styles` and copy the downloaded catppuccin sab file there.

4. Now right click on start logo on desktop, go to the last option preferences, it will open startallback settings.

5. Go the taskbar settings and change the taskbar location setting to **TOP**

6. In taskbar settings change the visual style to catppuccin (do the same for start menu)

DONE THE START MENU AND TASKBAR ARE DONE. :)

</details>

### Installing new right-click menu
<details close>
<summary>Follow this</summary>
<br>
Steps:
  
1. Install from [nilesoft shell](https://nilesoft.org/) or by running `winget install nilesoft.shell` in cmd

2. After installing your right-click menu will change and will have a lot more options.

3. You will have to install Catppuccin-Mocha-Pink.nss theme from [Catppuccin nilesoft](https://github.com/catppuccin/nilesoft-shell/blob/main/mocha/catppuccin-mocha-pink.nss)

4. After downloading the catppuccin-mocha-pink.nss file, open the file in notepad and **rename the file to theme.nss**

5. Copy the theme.nss file

6. Shift+right click on the taskbar>shell>open directory, this should open in file manager.

7. Go the folder `imports` and paste your theme.nss there.

8. Hold shift and right-click the taskbar and Click on **Exit Explorer**

DONE THE RIGHT CLICK MENU IS NOW THEMED. 💯

</details>

### Installing and configuring Alacritty(New Terminal)
<details close>
<summary>Follow this</summary>
<br>
Steps:

1. Intall [alacritty](https://alacritty.org/)

2. Opem alacritty once and close it.

3. Download my [alacritty.toml](https://github.com/notsuju/Make-Windows-Incredible/blob/main/alacritty.toml) file

4. Now copy this file and paste it in `C:\Users\SUJU\AppData\Roaming\alacritty` in file manager

DONE YOUR ALACRITTY THEME IS DONE.

</details>

### Installing keypirinha(App Launcher)
<details close>
<summary>Follow this(this could be a bit complicated but just follow the steps)</summary>
<br>
Steps:

1. Install Chololatey by running command prompt as administrator and paste this `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))` and hit enter and let it install until you see successful.

2. Now install Keypirinha by running this command `choco install keypirinha` in command prompt with administrator

3. Now go to `C:\ProgramData\chocolatey\lib\keypirinha\tools\Keypirinha` and create a shortcut of keypirinha.exe

4. Now **window+r** and type **shell:startup**

5. It will open in file manager

6. Move the shortcut to this location

7. Restart your computer

8. Now go to `C:\ProgramData\chocolatey\lib\keypirinha\tools\Keypirinha\default\App` and open keypirinha.ini file in notepad.

9. Close notepad and reopem notepad as administrator

10. Now copy the raw file from [here](https://github.com/notsuju/Make-Windows-Incredible/blob/main/Keypirinha.ini) by clicking the raw option

11. Now delete everything in file that you have opened in notepad and paste this new raw file in there and save.

12. Now do **win+ctrl+k** (we will change it)

13. In keypirinha search box search config and click on keypirinha: Configure

14. This is will open two text editor windows

15. Now just paste this

`[app]
hotkey_run = Alt+Space
[gui]
theme = catppuccin
show_on_taskbar = no
max_results = 10`

on the right window and save it by ctrl+s

DONE NOW YOU CAN USE ALT+SPACE TO CALL KEYPIRINHA WITH CATPPUCCIN THEME. :0

</details>

### Installing Catppuccin theme in firefox
<details close>
<summary>Follow this(this could be a bit complicated but just follow the steps)</summary>
<br>
Steps:

1. Open Firefox and type `about:config` in the address bar and search

2. It will say proceed with caution, just accept the ricks and continue

3. In about:config searxh for `legacyuserpro` and switch the value to true by **clicking the reversible button in the right hand corner**

![aboutconfig](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/cce6f26a-7ce5-4a88-a18c-e5343335e528)

5. Go to [here](https://github.com/mimipile/firefoxCSS/blob/main/userChrome.css) and copy the raw file

We are using a theme called [Another Online](https://github.com/mimipile/firefoxCSS/tree/main) by mimipile

5. Open firefox and type `about:profiles` in the address bar and search

6. Go the second option root directory and click open directory

![firefoxopendir](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/8e615d4c-07bf-4f93-9979-afdf854e002a)

8. Close firefox

9. Now here create a folder named `chrome`

10. Now go inside the chrome folder

11. Make two files inside called `userChrome.css` and `userContent.css`

12. Also make a folder named `img`

13. Now paste the raw file that was copied in step 4 in `userChrome.css` and save

14. Go to [link](https://github.com/notsuju/Make-Windows-Incredible/blob/main/userContent.css) and copy the raw file

15. Paste this raw file in `userContent.css` and save

16. Now pick downlaod image from [here](https://github.com/notsuju/Make-Windows-Incredible/tree/main/Wallpapers)

17. Copy the name of the image with file type `Example: 123.png` copy the whole thing 123.png

18. And paste that image in the `img` folder (this will be your firefox background image)

19. Now open `userContent` and look at **line 12** paste the copied name after `img/` and save

20. Close everything and reopen firefox (Your theme and img is work now)

21. Now go to [here](https://color.firefox.com/?theme=XQAAAAJDBAAAAAAAAABBqYhm849SCicxcUcPX38oKRicm6da8pFtMcajvXaAE3RJ0F_F447xQs-L1kFlGgDKq4IIvWciiy4upusW7OvXIRinrLrwLvjXB37kvhN5ElayHo02fx3o8RrDShIhRpNiQMOdww5V2sCMLAfehhp-xkeer3MCWdRzOxwUd1idIdYygjYcDC9HOohbgoQY1wJYK0MG9FFPmpCOo5rViKWXT2rMRBQb2guhvABroGB6LqX-HZ9JR9FU6ZnHTCdQPn261avChXEifYgCOyCKdS9ZoXxv_HHhkTIaEsdaPO9_OsUjQOnRR9pOQ-2-gaJG0tk5WJBmW2OdZHi6QoWbHvo-LCxDCc5eM3Jnlsv7tefW8SXXnLqRKzvRpV5w-LJMsxKo2sk_mbfjvCt5UXn08uJWISpZgv-55kH1p9oHbjThn2WEQRY5WG7yRe3QfTR0WgAOhFyS8twgohbNtAGIYntaJW-9ziKrBuB5ASBAQ_wKYehawNAyShIBulC6wkZK2RoN8CeDkNDHQH8xS1cfyPOuC1OiL9DwyNUyDzvtj_zmaZw) and save the color scheme

ALL DONE FIREFOX IS READY :)

</details>

### Installing Catppuccin theme in vs code
<details close>
<summary>Follow this(this could be a bit complicated but just follow the steps)</summary>
<br>
Steps:

1. Go to this [link](https://marketplace.visualstudio.com/items?itemName=AlexDauenhauer.catppuccin-noctis) and click on install and let it install on vs code

2. Now open vs code and do `ctrl+k+T` and search catppuccin noctis and click on it to apply.

ALL DONE VS CODE IS DONE.






