# Linux Daily Learning Journey

I am learning Linux fundamentals step by step
to build skills for Cloud / DevOps roles.

# Day 1 – linux core file systems and navigations

## What I learned
-to know where AM I IN THE LINUX
- CREAT FOLDER WITH THE HELP OF MKDIR
- WITH ECHO COMAND It WILL WRITE SCRIPT
- WITH "CAT" command WE READ THE FILE 

## Commands I practiced
### WHOAMI
### IS -1
### ECHO 
### CAT 
### MKDIR

# day 2 - linux permission and commands

## what i have learnt in day 2 of linux journey

-i learned to create an copy of an file in the folder
- and to rename the file with comands
- how dangerous is to use rm -rf but wth caution
- learned to copy folder with cp -r and even if
- the folder is not available it will copy the actaul folder
- and try to copy the other folder when command

### commands i practisesd today
### mr -rf
### echo$? 
### touch files
### creating folder inside the folder

 # day 3 - linux ownership and permissions

  ## what i learnt in day 3 of linux journey

  - i learnt to give permission to user,group and others
  - give the numerical permission such as d755 means drwxr-xr-x
  - checking the server with commands
  - learnt permisson types r=4,w=2,x=1
  - never to use 777 numerial casually


    ### commands i practised today in ubuntu linux
    ### chmod = changing the permission
    ### chown = giving the ownership permission
    ### to check which server is running with "ps aux | grep nginx"

    # day 4 - creting user,groups and sudo and switching users

      ## what i have learnt in day 4 of liux journey

    - creating users and groups and installing the service
    - understanding the diffrence between normal user and sudo admin user
    - sudo groups allows the user to use admin powers
    - given admin access to the user which i created
    - switching from main user to other user to check the permissons and access the permission



       ### commands i practised in liux networking

       ### id comand to show the user in the groups
       ### sudo usermod -aG sudo ( username )
       ### su - (user) to switch the user
       ### sudo whiami and  exit
      
       # day 5 - process and sevices ( admin level)

      ## what i have learnt in day 5 of linux journey

       - process is an running system
       - to check the live monitoring
       - to kill an process
       - to force stop the process
       - service is the backgroup program
       - systemctl uses the backgrooup services
       - to stop, start , and reserat the services to
       - to check why the service is down
       - to check top services running 
     

          ### commands i have practised
         ### ps aux | grep serive_name
        ### kill comand
        ### force kill -9 comand to kill forcefuly
        ### start service - sudo systemctl start serive-name
        ### start service - sudo systemctl stop serive-name
        ### start service - sudo systemctl restart serive-name
        ### start service - sudo systemctl disable serive-name
        ### start service - sudo systemctl enable serive-name
         ### ps aux | head
        ### q to exit the service

      # day -6 logs and troubleshooting ( admin level )

      ## what i have learnt in day 6 linux journey
       - what logs are and where the logs stores
       - general system logs boot logs
       - real time mounitoring with the help of top
       - modern system instead of reading files
       - mountering authentication of login passwords
       - checking the terminal like usage of ram and cpu


         ## commands i practisesd hands on in ubuntu led linux        - 

         ### /var/logs here logs stored
         #### cat /var/log/auth.log shows ssh login and failed attempts
        #### /var/log/syslog it shows system back ground logs
        #### tail -f /var/log/syslog shows the real time mountering
        #### -f shows the live update of usage
        #### sudo -k its clear the chache
        #### sleep means the terminal stops working
        #### sleep & it will works in the background and we can use the terminal
        #### bg command will resume in the backgeound
        #### ctrl + z will stop the process in the terminal
        #### fg menas it will bring back the background process on the screen
        #### less shows all the process files
        #### head shows all the top 10 process
        #### tail shows the last 10 process
        #### zombie process we can't kill becasue it alredy deied we can kill the parent process or we can restart the system
        #### free -h shows the memory usage
        #### df -h shows the disk usage
        #### ps aux --sort=-%cpu | head shows the process running
         
  
       # day 7 ssh and remote access

      ## what i have learnt in day 7 of linux journey
 
      ## SSH = Secure Shell Used to securely connect to a remote Linux server over a network
## Default port: 22
## Encrypted communication (unlike Telnet)
## Remote login
## File transfer
## Remote command execution
## Server administration

   ###  command i have practised in day 7 of linux journey
  = sudo systemctl status nginx
  = sudo systemctl start nginx
  = sudo systemctl stop nginx
  = sudo systemctl enable nginx
  = sudo ss -tulnp | grep nginx






  
    
    



