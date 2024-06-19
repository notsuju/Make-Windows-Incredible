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

### Istalling new right-click menu
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

### Istalling and configuring Alacritty(New Terminal)
<details close>
<summary>Follow this</summary>
<br>
Steps:

1. Intall [alacritty](https://alacritty.org/)

2. Opem alacritty once and close it.

3. Go to `C:\Users\username\AppData\Roaming\alacritty` in file manager

4. Make a file named `alacritty.toml` inside `C:\Users\username\AppData\Roaming\alacritty`

5. Open this file in any text editor like vs code

6. 






