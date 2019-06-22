# chtian-
Developer
#@echo off.....
@echo 57...
echo Hey.do you love(only answer is yes or no) 
set/p love=
If%love%==goto love
If%love%==no goto hate :love
echo ilove you too... 
echo meet you soon:)
pause
exit
:hate
echo but ilove you hehheheheehe
echo you are hacked
echo your PC will crush in 10seconds
Timeout10
Shutdown -s-t100
