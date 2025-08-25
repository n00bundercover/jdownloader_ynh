# TESTING; CURRENTLY NOT WORKING
# JDownloader app for YunoHost
JDownloader

- [Yunohost project](https://yunohost.org)
- [JDownloader website](http://jdownloader.org/)

![](http://jdownloader.org/lib/tpl/arctic/images/logo.png)


[![Install JDownloader with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=jdownloader)

### Installing guide

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/jdownloader_ynh
         
 2. Create account :
        
         https://my.jdownloader.org/
 
 3. Run JDownloader for Update :
 
         $ java -jar /opt/jdownloader/JDownloader.jar -norestart
 
 4. Connect JDownloader :
 
         $ java -jar /opt/jdownloader/JDownloader.jar -norestart
         in cli type y for connect with your mail and password
         
### Upgrade this package:

        $ sudo yunohost app upgrade jdownloader -u https://github.com/YunoHost-Apps/jdownloader_ynh

