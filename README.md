# Make-Windows-Incredible
In this guide, I will help you make your windows install better, this includes the following:
+ ✨This is a guide which will help you make your windows pc much more **secure** and **private** by disabling most of the Telemetry.
+ Plus this guide will aslo make your windows install look way more **beautiful** using Catppuccin theme for most things.
+ Installing some really useful programs.
> [!WARNING]
> This is going to be a long process and will take good amount of hard work.


## Screenshots

![mainsample](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/48226358-28ca-4632-bcb7-8743e95f3780)

![Screenshot 2024-06-19 102953](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/40572e80-b09c-4a86-939b-26a8d83be63e)

![Screenshot 2024-06-19 103208](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/9b7a4d7d-e6e0-407d-9b54-22417afea1d2)

![Screenshot 2024-06-19 103102](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/a60f8111-11ac-4f5c-898c-69d51067e1ca)

![Screenshot 2024-06-19 103409](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/febfe82b-2ac6-42eb-a4ea-fa92200c92ff)

![Screenshot 2024-06-19 231107](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/60d098e4-a3e2-4257-9b85-40ffc17baa59)

## Making Windows more Private
This is gonna include setting up a **SECURE DNS**, **HARDENING FIREFOX**, **REMOVING MOST OF THE TELEMETRY** and some more tips.
So lets get started.

### Installing and hardening firefox
<details close>
<summary>Click me</summary>
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

see here

![rawcopy](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/cbb5f86f-2bc9-4a04-b740-6ffd9cfffbc6)


**Search** `about:profiles` in the address bar of firefox

Under root directory click `Open Directory` or go to `C:\Users\SUJU\AppData\Roaming\Mozilla\Firefox\Profiles\PROFILENAME` in your file manager

![firefoxopendir](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/a9318b36-0abd-4675-891f-ec32eff6e2c1)

Create a file called **user.js** in the onpened directory and paste all of the raw file there and save it.
> You can make a file like user.js by changing the `txt` format to `js` see here

![userjss](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/4cbc0105-5d10-4f47-a6ef-e339f995314d)

5. Changing the search engine to brave (see here [article](https://search.brave.com/default))

> Go to https://search.brave.com/

> Right click on the address bar

> There should be an option to add brave as a searxh engine just click + icon on brave logo

> Now go to firefox settings>search>**Change the search engine to barve**

Now restart firefox and its hardened. Good job!

</details>

### Disabling most of the telemetry by microsoft🎢
<details close>
<summary>Click me</summary>
<br>
  
 For this I would highly recommend to watch this **[video](https://www.youtube.com/watch?v=VU9L0udNV9M&t=657s)** by The PC Security Channel, its really easy to follow.

</details>

### Using a secure DNS
<details close>  
<summary>Click me</summary>
<br>
  
I will be showing how to set up [nextdns](https://nextdns.io/)

Steps:

> [!NOTE]
> Best way of doing this is to follow the steps given on the setup page of [nextDNS](https://nextdns.io/) (recommended)


1. Go to [nextdns](https://nextdns.io/) and make an account

2. Open the Settings app

3. Go to Network & internet>Wifi>Hardware properties

4. Click the Edit button next to DNS server assignment

5. Select manual and Enable IPv4

6. Check the DNS Servers and put those values in **Preferred DNS** and **Alternate DNS**

7. On (mannual template) add your DNS-over-HTTPS.

</details>

## Making Windows beautiful
Time to make everything catppuccin theme.

### Installing Startallback and configuring it

#### Preview

![Screenshot 2024-06-19 222506](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/db371ca4-b210-4f71-8db4-5d10ccab6bc7)

<details close>
<summary>Click me</summary>
<br>
Steps:

You can follow this amazing [video](https://www.youtube.com/watch?v=kvpZx_SP2SM&list=PLGWgbaPiQ4hp4mYdaoVYnNZzzEym93d0t&index=5) by **VIN STAR** or **follow the following steps**
  
1. Install startallback from [here](https://startallback.com/)

2. Download this [file](https://github.com/notsuju/Make-Windows-Incredible/blob/main/Catppuccin%20SAB.msstyles)

HOW TO DOWNLOAD A RAW FILE SEE HERE

![rawdown](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/65a32d0e-953e-4bbd-bb76-90ad193a0ec5)

4. Go to `C:\Program Files\StartAllBack\Styles` and copy the downloaded catppuccin sab file there.

5. Now right click on start logo on desktop, go to the last option preferences, it will open startallback settings.

see here

![startprop](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/b7b70bf5-2510-401b-9a3e-faf27874c757)

7. Go the taskbar settings and change the taskbar location setting to **TOP**

8. In taskbar settings change the visual style to catppuccin (do the same for start menu)

DONE THE START MENU AND TASKBAR ARE DONE. :)

</details>

### Installing new right-click menu

#### Preview

![rightclick](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/298319c3-b57b-4239-a66d-d6ad2aa2c9e0)

<details close>
<summary>Click me</summary>
<br>
Steps:
  
1. Install from [nilesoft shell](https://nilesoft.org/) or by running `winget install nilesoft.shell` in cmd

2. After installing your right-click menu will change and will have a lot more options.

3. You will have to downlaod Catppuccin-Mocha-Pink.nss theme from [Catppuccin nilesoft](https://github.com/catppuccin/nilesoft-shell/blob/main/mocha/catppuccin-mocha-pink.nss)

HOW TO DOWNLOAD A RAW FILE SEE HERE

![rawdown](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/1a3b4c18-39fa-401b-861f-3aee6c230272)


5. After downloading the catppuccin-mocha-pink.nss file, open the file in notepad and **rename the file to theme.nss**

6. Copy the theme.nss file

7. Shift+right-click on the taskbar

8. Then clcik shell>open directory, this should open in file manager.

9. Go the folder `imports` in that directory and paste your theme.nss there.

10. Hold shift and right-click the taskbar and Click on **Exit Explorer**

DONE THE RIGHT CLICK MENU IS NOW THEMED. 💯

</details>

### Installing and configuring Alacritty(Terminal)

#### Preview

![Screenshot 2024-06-19 222729](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/2a806357-7ea1-424f-8a4f-7ab2a4854910)

<details close>
<summary>Click me</summary>
<br>
Steps:

1. Intall [alacritty](https://alacritty.org/)

2. Opem alacritty once and close it.

3. Download my [alacritty.toml](https://github.com/notsuju/Make-Windows-Incredible/blob/main/alacritty.toml) file

HOW TO DOWNLOAD A RAW FILE SEE HERE

![rawdown](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/65a32d0e-953e-4bbd-bb76-90ad193a0ec5)


5. Now copy this file and paste it in `C:\Users\username\AppData\Roaming\alacritty` in file manager

DONE YOUR ALACRITTY THEME IS DONE.

</details>

### Installing keypirinha(App Launcher)

#### Preview

![Screenshot 2024-06-19 223944](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/2bede3d8-1a78-40f8-8b3b-44a72f1a890a)

<details close>
<summary>Click me(this could be a bit complicated but just follow the steps)</summary>
<br>
Steps:

1. Install Chololatey by running command prompt as administrator and paste this `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))` and hit enter and let it install until you see successful.

2. Now install Keypirinha by running this command `choco install keypirinha` in command prompt with administrator

3. Now go to `C:\ProgramData\chocolatey\lib\keypirinha\tools\Keypirinha` and create a shortcut of keypirinha.exe

see here
![key](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/6321d525-e3e4-48c2-8961-39bb738e4ed1)

5. Now **window+r** and type **shell:startup**

6. It will open in file manager

7. Move the shortcut to this location

8. Restart your computer

9. Now go to `C:\ProgramData\chocolatey\lib\keypirinha\tools\Keypirinha\default\App` and open keypirinha.ini file in notepad.

10. Close notepad and reopem notepad as administrator

11. Now copy the raw file from [here](https://github.com/notsuju/Make-Windows-Incredible/blob/main/Keypirinha.ini) by clicking the raw option

12. Now delete everything in file that you have opened in notepad and paste this new raw file in there and save.

13. Now do **win+ctrl+k** (we will change it alt+space later)

14. In keypirinha search box search config and click on keypirinha: Configure

see here

![Screenshot 2024-06-19 224228](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/284a9a92-03e0-4fc4-a5e3-a9c999628af5)

15. This is will open two text editor windows

16. Now just paste this

`[app]
hotkey_run = Alt+Space
[gui]
theme = catppuccin
show_on_taskbar = no
max_results = 10`

on the right window and save it by ctrl+s

see here

![Screenshot 2024-06-19 224228](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/96b58f72-ab72-41bf-b226-3797779fddb1)

DONE NOW YOU CAN USE ALT+SPACE TO CALL KEYPIRINHA WITH CATPPUCCIN THEME. :0

</details>

### Installing Catppuccin theme in firefox

#### Preview

![Screenshot 2024-06-19 225709](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/2d54de38-6519-4852-8dab-88caca3acc59)

<details close>
<summary>Click me</summary>
<br>
Steps:

1. Open Firefox and type `about:config` in the address bar and search

2. It will say proceed with caution, just accept the ricks and continue

3. In about:config searxh for `legacyuserpro` and switch the value to true by **clicking the reversible button in the right hand corner**

![aboutconfig](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/cce6f26a-7ce5-4a88-a18c-e5343335e528)

4. Go to [here](https://github.com/mimipile/firefoxCSS/blob/main/userChrome.css) and copy the raw file

We are using a theme called [Another Online](https://github.com/mimipile/firefoxCSS/tree/main) by mimipile

5. Open firefox and type `about:profiles` in the address bar and search

6. Go the second option root directory and click open directory

![firefoxopendir](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/8e615d4c-07bf-4f93-9979-afdf854e002a)

8. Close firefox

9. Now here create a folder named `chrome`

10. Now go inside the chrome folder

11. Make two files inside called `userChrome.css` and `userContent.css`

HOW TO MAKE FILE WITH `.css` type SEE HERE

![userjss](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/69a24f5e-dd6a-4b71-851f-d9ef97eec7e1)

13. Also make a folder named `img`

It should look like this

![Screenshot 2024-06-19 230109](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/0d204ef3-1028-485a-aa3e-be25508449c8)

15. Now paste the raw file that was copied in **step 4** in `userChrome.css` and save

16. Go to [link](https://github.com/notsuju/Make-Windows-Incredible/blob/main/userContent.css) and copy the raw file

17. Paste this raw file in `userContent.css` and save

18. Now pick downlaod image from [here](https://github.com/notsuju/Make-Windows-Incredible/tree/main/Wallpapers)

19. Copy the name of the image with file type `Example: 123.png` copy the whole thing 123.png

20. And paste that image in the `img` folder (this will be your firefox background image)

21. Now open `userContent` and look at **line 12** paste the copied name after `img/` and save

22. Close everything and reopen firefox (Your theme and img is work now)

23. Now go to [here](https://color.firefox.com/?theme=XQAAAAJDBAAAAAAAAABBqYhm849SCicxcUcPX38oKRicm6da8pFtMcajvXaAE3RJ0F_F447xQs-L1kFlGgDKq4IIvWciiy4upusW7OvXIRinrLrwLvjXB37kvhN5ElayHo02fx3o8RrDShIhRpNiQMOdww5V2sCMLAfehhp-xkeer3MCWdRzOxwUd1idIdYygjYcDC9HOohbgoQY1wJYK0MG9FFPmpCOo5rViKWXT2rMRBQb2guhvABroGB6LqX-HZ9JR9FU6ZnHTCdQPn261avChXEifYgCOyCKdS9ZoXxv_HHhkTIaEsdaPO9_OsUjQOnRR9pOQ-2-gaJG0tk5WJBmW2OdZHi6QoWbHvo-LCxDCc5eM3Jnlsv7tefW8SXXnLqRKzvRpV5w-LJMsxKo2sk_mbfjvCt5UXn08uJWISpZgv-55kH1p9oHbjThn2WEQRY5WG7yRe3QfTR0WgAOhFyS8twgohbNtAGIYntaJW-9ziKrBuB5ASBAQ_wKYehawNAyShIBulC6wkZK2RoN8CeDkNDHQH8xS1cfyPOuC1OiL9DwyNUyDzvtj_zmaZw) and save the color scheme

ALL DONE FIREFOX IS READY :)

</details>

### Installing Catppuccin theme in vs code

#### Preview

![Screenshot 2024-06-19 103409](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/5c577a02-9978-4dee-b7e9-55be4903589e)

<details close>
<summary>Follow this</summary>
<br>
Steps:

1. Go to this [link](https://marketplace.visualstudio.com/items?itemName=AlexDauenhauer.catppuccin-noctis) and click on install and let it install on vs code

2. Now open vs code and do `ctrl+k+T` and search catppuccin noctis and click on it to apply.

ALL DONE, VS CODE IS DONE.

</details>

## Installing Catppuccin theme in spotify

#### Preview

![Screenshot 2024-06-19 103208](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/1258ccbd-0d54-4c75-93a3-2fa38ad31660)

<details close>
<summary>Click me</summary></summary>
<br>
For this we will have to install spicetify.
Steps:

1. Uninstall Spotify

2. Go to [Spotify website](https://www.spotify.com/de-en/download/windows/) and click on download directly from spotify

see here

![spotifydown](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/c1b3892b-13c2-4142-b37e-5c5b10399f2d)

3. Install Spotify

4. Install [Spicetify](https://spicetify.app/) by running this command in powershell `iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex`

5. It will ask if you want to install marketplace type `y`

6. Once the installion is done

7. Open Spotify and log-in

8. A new option of store will be available

9. Click on it and go to themes and install **text darkthemer** and reload

10. And choose the **rosepine flavour**

see here

![spotifymarket](https://github.com/notsuju/Make-Windows-Incredible/assets/131643792/bc4efbfe-1e06-4029-982e-4884a0ef40f8)

ALL DONE EXPLORE THE STORE AND INSTALL THINGS THAT YOU LIKE

</details>

## Some extra Tips and programs to install (OPTIONAL)
<details close>
<summary>Click me</summary></summary>
<br>
  
+ Install [revo](https://www.revouninstaller.com/) super powerful uninstaller
  
+ Install [kde connect](https://kdeconnect.kde.org/) connect your phone and pc over wifi and do some amazing things(You will have to downlaod it on both pc and mobile)

+ Install [Proton vpn](https://protonvpn.com/) really good vpn with some free countries

+ I will recommend using [proton mail](https://proton.me/mail) instead of gmail (you can use it free)

+ I will recommend using a password manager like [proton](https://proton.me/pass) (you can use it free)

</details>



