# strongloop

Testing strongloop

## Installation

####1. Install node

  - https://nodejs.org/en/

####2. Install npm

```sh
$ sudo apt-get install npm
```

####3. Install strongloop

```sh
$ npm install -g strongloop
```

####4. Creating new API

```sh
$ slc loopback
$ input app name
```

[Project layout reference](https://docs.strongloop.com/display/public/LB/Project+layout+reference)

####5. Run Arc API

```sh
$ cd myapp
$ slc arc
```
  And login

####6. Install docker and PostgreSQL

- https://www.docker.com/docker-toolbox
- pgAdmin http://www.pgadmin.org/download/
- PostgreSQL 9.4.5 http://www.postgresql.org/download/

####7. Install Strongloop Postgres connector

#####Run

```sh
$ npm install loopback-connector-postgresql --save
```

#####Connector settings


The connector can be configured using the following settings from the data source.
```
url: The URL to the database, such as 'postgres://user:myuserpassword@localhost:5432/dev'
host or hostname (default to 'localhost'): The host name or ip address of the PostgreSQL DB server
port (default to 5432): The port number of the PostgreSQL DB server
username or user: The user name to connect to the PostgreSQL DB
password: The password
database: The PostgreSQL database name
```

