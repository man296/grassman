# **HOW TO GET GRASS USER ID USING ANDROID DEVICE**  

Download and install [mises browser](https://play.google.com/store/apps/details?id=site.mises.browser).

Donwload and install [termux]
(https://f-droid.org/repo/com.termux_1020.apk).

Login to grass web and go to the dashboard, then open the Developer Tools in the mises browser.

Go to the **Console** tab and paste this code:

> localStorage.getItem('userId')

If you can't paste, type `allow pasting` and press Enter, then paste the line above.

## **CONFIGURE TERMUX**

After Installing Termux, Make Sure You Allowed Storage Permission On Termux (device app) Settings. Or Run This Command In Termux -

> termux-setup-storage

**Install Python 3.10 -**

> pkg update && upgrade
 
> pkg install tur-repo
 
> pkg install python-is-python3.10

> pkg install -y rust binutils
 
> CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin

# **GIT CLONE THIS SCRIPT**

> git clone https://github.com/man296/grassman.git

**CHANGE DIRECTORY TO SCRIPT FOLDER**

> cd grassman

**Install Requirements**

> pip install --upgrade pip

> pip install -r requirements.txt

# RUN SCRIPT
> python grassdesktop.py

or

> python grassnode.py

