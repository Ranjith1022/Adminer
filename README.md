<center>
<img src= "https://ps.w.org/pexlechris-adminer/assets/banner-1544x500.jpg?rev=2685110" alt='AdminerLogo'>
<center>

# Adminer (Database-Management-Tool)

Adminer is a tool for managing content in databases. It natively supports MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch and MongoDB. Adminer is distributed under Apache license in a form of a single PHP file.Graphical User Interface (GUI) Tool for Database Management System.
Replace phpMyAdmin with Adminer and you will get a tidier user interface, better support for MySQL features, higher performance and more security

   
  ## Requirements
  o	PHP version 5+ with enabled sessions
  
  o	Apache WebServer
  
  
## Installation
Adminer on Ubuntu 20.04 LTS

#### Step 1:
Update and Upgrade 
```
$ sudo apt update && upgrade
```

#### Step 2:
Install <strong>```Apache2 WebServer```</strong>
```
$ sudo apt install apache2
```

#### Step 3:
Install <strong>```PHP```</strong> version 5+
```
$ sudo apt install --no-install-recommends php8.1
```

#### Step 4:
Install <strong>```git```</strong>
```
$ sudo apt install git
```

#### Step 5:
<strong>```Goto```</strong> site path
```
$ mkdir /var/www
$ cd /var/www
```


#### Step 6:
<strong>```Clone```</strong> the Project Documents
```
$ git clone https://github.com/Ranjith1022/Adminer.git
```

#### Step 7:
Default <strong>```Apache2 configuration```</strong> for Adminer <a href="https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-20-04">Click here</a> for Manual configuration.

```diff
+ change DocumentRoot path
```
```
$ vim /etc/apache2/sites-available/000-default.conf # change DocumentRoot path
```
```diff
<VirtualHost *:80>
  ...
    ServerAdmin webmaster@localhost
    DocumentRoot /var/www/Adminer
   ...
    ErrorLog ${APACHE_LOG_DIR}/error.log
    CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>
```


#### Step 8:
<strong>```Finally```</strong> check the below URL in your web broser
```
$ http://localhost
```


## Adminer development priorities are:
1. Security

2. User experience

3. Performance

4. Feature set

5. Size.

## Features

<li><strong>Connect</strong> to a database server with username and password</li>
	<li>Select an existing <strong>database</strong> or create a new one</li>
	<li>List fields, indexes, foreign keys and triggers of table</li>
	<li>Change name, engine, collation, auto_increment and comment of <strong>table</strong></li>
	<li>Alter name, type, collation, comment and default values of <strong>columns</strong></li>
	<li>Add and drop tables and columns</li>
	<li>Create, alter, drop and search by <strong>indexes</strong> including fulltext</li>
	<li>Create, alter, drop and link lists by <strong>foreign keys</strong></li>
	<li>Create, alter, drop and select from <strong>views</strong></li>
	<li>Create, alter, drop and call <strong>stored procedures and functions</strong></li>
	<li>Create, alter and drop <strong>triggers</strong></li>
	<li><strong>List data</strong> in tables with search, aggregate, sort and limit results</li>
	<li>Insert new <strong>records</strong>, update and delete the existing ones</li>
	<li>Supports all <strong>data types</strong>, blobs through file transfer</li>
	<li>Execute any <strong>SQL command</strong> from a text field or a file</li>
	<li><strong>Export</strong> table structure, data, views, routines, databases to SQL or CSV</li>
	<li>Print <strong>database schema</strong> connected by foreign keys</li>
	<li>Show <strong>processes</strong> and kill them</li>
	<li>Display <strong>users and rights</strong> and change them</li>
	<li>Display <strong>variables</strong> with links to documentation</li>
	<li>Manage <strong>events</strong> and <strong>table partitions</strong> (MySQL 5.1)</li>
	<li>Schemas, sequences, user types (PostgreSQL)</li>
	<li>Extensive <strong>customization</strong> options</li>
  
  ```diff
  
  + Available in many languages (43) including English - Create a new translation
  
  + Free for commercial and non-commercial use (Apache License or GPL 2)
  
```
  


  ## Software works with:
  MySQL
  
  MariaDB
  
  PostgreSQL
  
  SQLite
  
  MS SQL
  
  Oracle
  
  Elasticsearch
  
  MongoDB
  
  SimpleDB (plugin)
  
  Firebird (plugin)
  
  ClickHouse (plugin)
  
  Improve your driver
