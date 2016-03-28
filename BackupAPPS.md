because we install new release almost every day here is script for linux (will add for windows when i find it how )
IF YOU DON'T KNOW WHAT IS ADB OR COMMAND LINE DO NOT TRY THIS
DO NOT REPORT PROBLEMS HERE IF COMMAND NOT WORKS FOR YOU


in terminal #
adb shell ls /data/app/**.apk | tr '\r' ' ' | xargs -n1 adb pull # this is to back up all apps to home folder**

>LINUX
ls -1 **.apk | xargs -l adb install # to install all backed up apps**



WINDOWS>
or %f in (c:\appdirectory\**.apk) do adb install %f # to install all backed up apps**


adb shell ls /data/app/**.apk | tr "\n\r" " " | xargs -n1 adb pull # this is to**

some apps guis

https://code.google.com/p/mass-apk-installer/
source for scripts > http://stackoverflow.com/questions/1...-multiple-apks

IF YOU DON'T KNOW WHAT IS ADB OR COMMAND LINE DO NOT TRY THIS
DO NOT REPORT PROBLEMS HERE IF COMMAND NOT WORKS FOR YOU




you can try to pull it an push it when install new build
DO NOT REPORT PROBLEMS HERE IF YOU TRY THIS