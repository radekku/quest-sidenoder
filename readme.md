**SideNoder** - A **cross platform sideloader** for Quest(1&2) standalone vr headset.

![screen](.github/screen.gif)
### Installation:
Download and run one of the available binaries: (currently no binary, pls run manually)
```
https://github.com/whitewhidow/quest-sidenoder/releases
```
or clone the repo, and run the app manually (requires node and git) :
```
git clone https://github.com/whitewhidow/quest-sidenoder.git
cd quest-sidenoder/
npm install
npm start
```
Please report any issues here :

https://github.com/whitewhidow/quest-sidenoder/issues | https://t.me/whitewhidow | https://discord.gg/pVMsAyYhAf

## Dependencies:



#### linux:
Install git, adb and rclone using these commands:
```
sudo apt install git
sudo apt install nodejs
sudo apt install adb
curl https://rclone.org/install.sh | sudo bash
```



#### mac/osx:
Install git, adb, nodejs, osxfuse and rclone using these commands:
```
brew install git
brew cask install android-platform-tools
brew install node
curl https://rclone.org/install.sh | sudo bash
brew cask install osxfuse
```




#### windows:
Download and unzip adb, aapt and rclone from the below links and add their directories to the $PATH environment variable:
```
https://dl.google.com/android/repository/platform-tools-latest-windows.zip
https://androidaapt.com/
https://downloads.rclone.org/v1.53.2/rclone-v1.53.2-windows-amd64.zip
```
<details>
<summary>What does "add to PATH" mean?</summary>
After you download and unzip adb, aapt, and rclone you will have 3 new folders
You should then add these 3 new directories, to the existing PATH environment variable of windows.
  
How to add a directory to PATH: https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/

More info about what PATH is and why you are adding things to it: https://superuser.com/a/284351
</details>



Install git and node from:
```
https://git-scm.com/download/win
https://nodejs.org/en/download/
```
Install winfsp and reboot:
```
https://github.com/billziss-gh/winfsp/releases/download/v1.8/winfsp-1.8.20304.msi
```



<!--
https://stackoverflow.com/a/44272417/1501189
https://www.xda-developers.com/adb-fastboot-any-directory-windows-linux/

adb (install globally)
https://dl.google.com/android/repository/platform-tools-latest-windows.zip

rclone (install globally)
https://downloads.rclone.org/v1.53.2/rclone-v1.53.2-windows-386.zip
https://downloads.rclone.org/v1.53.2/rclone-v1.53.2-windows-amd64.zip

winfsp (reboot)
https://github.com/billziss-gh/winfsp/releases/download/v1.8/winfsp-1.8.20304.msi

-->
