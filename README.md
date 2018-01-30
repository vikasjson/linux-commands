                                                  # linux-commands
                                        linux commands to perform operations 

1. check internet connecton in centos by below command:

   nmcli d
   
2. connect internet in centos :

   nmtui
   
3. get default target which is selected Graphical/Command line :

   systemctl get-default
   
4. set default target graphical :

   systemctl set-default graphical.target
   
5. install GUI in centos :

   yum -y group install "GNOME Desktop" "Graphical Administrative Tools"

6. Zip a directory or file :

   zip -r __new file name___ ___directory or file name which is to zip___

   
