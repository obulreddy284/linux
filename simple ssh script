#this is a script to ssh to multiple hosts and perform an action

#!/bin/bash
hosts=(hostname1 hostname2)
read -sp "enter password" password
for host in "${hosts[@]}";
 do
  sshpass -p $password ssh username@$host 'hostname;ulimit -n;exit;'>>/home/hary/obul.txt
done
---------------------------------------------------------------------------------------

method 2
-------------
pdsh -R ssh -w ^nodes 'cd /home/hary;ls -ltrh|grep try;exit;'>>/home/hary/obul.txt 
