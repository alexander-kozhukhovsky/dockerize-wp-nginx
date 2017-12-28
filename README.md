## Execute the following:

1. Download or clone this repository.
2. Open **docker-compose.yml** file and set your preferences (or leave it default).
3. Open **nginx/wordpress.conf** file folder:
```
cd nginx/
nano wordpress.conf
```
4. Change your test **server_name** on line **3** (default: *demo.big*).
5. Add server_name to your hosts file:
```
127.0.0.1   demo.big
```
6. Execute the following to startup the application (see [more](https://docs.docker.com/compose/reference/)):
```
docker-compose up -d
```

## Now You can:
- Access your WordPress site with http://yourservername
- Modify your WordPress files inside **wordpress** folder
- Access phpMyAdmin with http://yourIP:8080