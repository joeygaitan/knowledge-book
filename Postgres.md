### This is all for a linux terminal or unix. Like ubuntu, unix, etc. Not powershell...

# How to install Postgresql to WSL 2
* https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-database

## How to start up Postgresql
* ```sudo service postgresql start```

## Status of Postgresql running
* ```sudo service postgresql status```

## How to turn off Postgresql
* ```sudo service postgresql stop```

# Create A user
* ```sudo -u postgres createuser <username>```

## login into
* ```sudo psql -u postgres```

## Alter user privelages Inside of postgres terminal from command above (sudo psql -u postgres) this one....

* give the new created user super user so they can create database and such

``` ALTER ROLE misterjoe WITH SUPERUSER;```

* Give your user a password

* ```ALTER ROLE misterjoe WITH PASSWORD '1234';```

## If you somehow break this you can easily remove a role by dy dropping it. If the user has superuser they can't be dropped. Here's how to drop superusers (inside of the psql terminal...)

* ``` REASSIGN OWNED BY misterjoe to postgres; ```

* Now you can drop them like this

* ``` DROP ROLE misterjoe;```

## Test out your role by logging into postgres terminal with your new username!

* ``` psql -U misterjoe -d postgres ```

## How to create a database

* ```CREATE DATABASE dbname;```
