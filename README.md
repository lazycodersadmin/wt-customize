# Make Your Terminal Awesome

### 1. Install Windows Terminal

- Go to Microsoft Store
- Search for windows terminal
- Click on the install button
  <img src="https://raw.githubusercontent.com/lazycodersadmin/wt-customize/main/images/1.png" />

### 2. Install FiraCode Nerd Fonts

- Download FiraCode Nerd Fonts from [here](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/FiraCode.zip).
- Extract the zip into a folder.
- Select all items, right click and click Install for all Users.

### 3. Install Git (if not already)

- Download git installer from [here](https://git-scm.com/download/win).
- Just double tap the installer and keep doing next until it installs.

### 4. Install Oh My Posh

- Open powershell with administrator privileges.
- Install posh git:<br/>
  `Install-Module posh-git -Scope CurrentUser`
- Install oh-my-posh:<br/>
  `Install-Module oh-my-posh -Scope CurrentUser`

### 5. Install PSReadline

- Execute this command in powershell:<br/>
  `Install-Module -Name PSReadLine -Scope CurrentUser -Force -SkipPublisherCheck`

### 6. Edit powershell config

- In powershell, type:<br/>
  `notepad $PROFILE`
- In the notepad window, paste the following & save:<br/>
  `Import-Module posh-git`<br/>
  `Import-Module oh-my-posh`<br/>
  `Set-PoshPrompt ZASH`<br/>
  `cls`

### 7. Add background image

- Copy the path of your image you want to set as terminal background (could be gif, jpg, png, jpeg).

### 8. Edit the settings json

- Press Windows+R, type wt and press enter, if everything went right windows terminal will open.
- From there open settings by tapping the small down arrow at the top.
  <img src="https://raw.githubusercontent.com/lazycodersadmin/wt-customize/main/images/2.png">
- At the bottom left, tap the settings icon.
  <img src="https://raw.githubusercontent.com/lazycodersadmin/wt-customize/main/images/3.png">
- Remove everything and paste the content of settings.json in this directory.
- Change the path of your background image & icon.png.
  <img src="https://raw.githubusercontent.com/lazycodersadmin/wt-customize/main/images/4.png">

### Enjoy your new terminal :)
