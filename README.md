<b>backupRESSettings</b>

<b>The first test relase is out!</b>
    If you would like to help in testing please download the most recent relase and make sure that all your RES browser installs are detected.  If any are not please submit an issue and include your OS, browser name, and if you know it the location the browser stores the RES settings file at.  Thanks!

<b>IMPORTANT!</b>
    I have started working on re-writing the idea behind the backupRESSetting script into a cross-platform Java application. At first I will be implementing the browsers listed [here](http://www.reddit.com/r/Enhancement/wiki/backing_up_res_settings). However, eventually I will be willing to add support for any browser or OS that has not been covered. This readme will be updated more as the project develops.

<b>What:</b> The backupRESSettings.sh script will search for RES (Reddit Ehancement Suite) installs on your computer
and make a copy of them in an archive at a location you choose.

<b>Why:</b> Backups are good, and especially right now for firefox users because firefox has been deleting res settings on reset.

<b>Who:</b> This script currently only works for users running Mac OS X. I am currently working on re-writing into a cross-platform
version.

<b>How:</b> The script works by checking the location of many different locations different browsers use to store your RES settings.  Then if
the file is found it is added to a backup file which is stored at the location you specify.

<b>Where:</b> Check the releases for the latest working version, or download the latest commit.
