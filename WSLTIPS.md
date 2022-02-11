### apple version of open .
nautilus .
https://askubuntu.com/questions/976744/open-a-folder-in-file-manager-in-win10-wsl-while-in-ubuntu-command-line

### built in way wsl
explorer.exe .

### Helpful windows 10 commands
Windows key + D = hides all windows
Windows key + shift + 2 = open new ubuntu window

### vscode commands
control + alt + up or down = multiple lines

### google chrome key commands
control + tab = goes right
control + shift + tab = goes left

# Python Commands for vitural environment 

python3 -m venv env

source env/bin/activate

# how to kill a port

sudo lsof -i :5955 port number

sudo kill -9 PID number

# mongo setup wsl tutorial
https://github.com/michaeltreat/Windows-Subsystem-For-Linux-Setup-Guide/blob/master/readmes/installs/MongoDB.md

# psql how to start

sudo service postgresql start
sudo service postgresql restart
sudo service postgresql status
sudo service postgresql stop


* how to connect to your desired database
psql -U postgres my_database

# how to work with my mysql

sudo service mysql restart
sudo service mysql stop
sudo service mysql start
sudo service mysql status

sudo mysql -u root -p 
mysql -u root -p

how to change the root password
ALTER USER 'root'@'localhost' IDENTIFIED BY 'MyNewPass';

## mongodb

### install process

* sudo apt update
* sudo apt-get install mongodb

#### commands

```bash
sudo service mongodb status 
sudo service mongodb start
sudo service mongodb stop
```