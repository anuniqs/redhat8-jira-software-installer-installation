## JIRA Software Installer Installation —

### GYAN —

Jira is a proprietary issue tracking product developed by Atlassian that allows bug tracking and agile project management.

https://confluence.atlassian.com/adminjiraserver/installing-jira-applications-on-linux-938846841.html

### 1. Download Jira

https://www.atlassian.com/software/jira/download

Choose Linux 64 Bit and down required version , "atlassian-jira-software-8.13.2-x64.bin"

### 2. Copy to server

[root@192 anup]# ls -ltr

[root@192 anup]# chmod a+x atlassian-jira-software-8.13.2-x64.bin

[root@192 anup]# ls -ltr


### 3. Run the installer

[root@192 anup]# ./atlassian-jira-software-8.13.2-x64.bin


Follow the prompts to install Jira. You'll be asked for the following info -
 
**Install type –** choose option 2 (custom) for the most control. 

**Destination directory –** this is where Jira will be installed.

**Home directory –** this is where Jira data like logs, search indexes and files will be stored.

**TCP ports –** these are the HTTP connector port and control port Jira will run on. Stick with the default unless you're running another application on the same port.

**Install as service –** this option is only available if you ran the installer as sudo. Once installation is complete head to http://localhost:8080 in your browser to begin the setup process. 

(Replace 8080 if you chose a different port during installation) . 
