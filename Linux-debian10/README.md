# Installation Gears

This is my personal setting 

## BunsenLabs Litium

BunsenLabs Linux is a distribution offering a light-weight and easily customizable Openbox desktop.

### Setting menu

go to `menu` > `Preferences` > `jgmenu` > `Edit Menu Content`

in the last of line in file `prepend.csv` under `^tag(apps)`, add the following lines

```csv
^tag(apps)
Back,^back()
chromium, /snap/bin/chromium
pycharm, /snap/bin/pycharm-community
postman, /snap/bin/postman
vsCode, /snap/bin/code
codium, /snap/bin/codium
subl, /snap/bin/subl
telegram, /snap/bin/telegram-desktop,
termius, /snap/bin/termius-app,
skype, /snap/bin/skype
mySql-Workbench, /snap/bin/mysql-workbench-community
ooffice, /snap/bin/onlyoffice-desktopeditors
sftpclient, /snap/bin/sftpclient
flameshot, /snap/bin/flameshot
digikam, /snap/bin/digikam
dbeaver, /snap/bin/dbeaver-ce

```

### Usefull command

1. view list software via snap `snap list`
2. restart the user `su -l <username>`
3. `which` - check which go (or ruby, or other app) installation path is used `which go`
4. `whereis` - check where app installation are located, example `whereis go`