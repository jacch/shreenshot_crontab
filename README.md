
### install default ubuntu screen shot scrot
sudo apt-get install scrot


### shreenshot_crontab
SAVE SCREEN EVER 1 HOURS BY CRONTAB

###set up crontab

10 * * * * env DISPLAY=:1 ~/screenshot_crontab/shot.sh

#
2019.12.13
create Directories by date

