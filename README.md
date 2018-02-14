                                                  # linux-commands
                                        linux commands to perform operations 

1. check internet connecton in centos by below command :

  # nmcli d
   
2. connect internet in centos :

   nmtui
   
3. get default target which is selected Graphical/Command line :

   systemctl get-default
   
4. set default target graphical :

   systemctl set-default graphical.target
   
5. install GUI in centos :

   yum -y group install "GNOME Desktop" "Graphical Administrative Tools"

6. Zip a directory or file :

   zip -r [new file name] [directory or file name which is to zip]

7. unzip a file :

   unzip [file_name]
   
8. install screen recorder in linux :
   
   sudo yum install recordmydesktop
   
9. start recording :
    
     recordmydesktop
     
10.     
