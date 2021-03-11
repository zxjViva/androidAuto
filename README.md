# androidAuto

android 10  
 .\emulator.exe -avd test -writable-system  
 adb root  
 adb remount  
https://blog.csdn.net/u010651541/article/details/53163542  
app_process -Djava.class.path=newlib.jar  /data/local/tmp com.jviva.lib.MyClassKt
.\dx.bat --dex --output=D:\zxj_doc\wukong\lib\build\libs\newlib.jar D:\zxj_doc\wukong\lib\build\libs\lib.jar
