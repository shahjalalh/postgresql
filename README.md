# Install PostgreSQL and pgAdmin4 with Docker

## Setup:

**Create a folder inside cloned repo -**
```
$ mkdir pgadmin4
$ mkdir pg-data
```

**Running the server:**
```
$ docker-compose up -d
```

**Stopping the server:**
```
$ docker-compose down
``` 

Now browse with the browser:

localhost:8888

Login to pgAdmin 4
```
user: shahjalal.tipu@gmail.com
pass: admin1234
```

<img src="./images/1-pgadmin4-login.png">

Connect with the PostgreSQL **Object > Create > Server**

```
Name: postgres
Host name/address: postgress
Port: 5432
Username: postgres
Password: postgres
Save password: [check] 
```

<img src="./images/2-postgres-connection.png">

<img src="./images/3-pgadmin4-connected-with-postgres.png">