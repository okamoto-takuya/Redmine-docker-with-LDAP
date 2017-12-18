# Redmine on docker with LDAP

## Usage

1. Get docker-compose.yml

```
$ cd <your directory>
$ git clone https://github.com/okamoto-takuya/Redmine-docker-with-LDAP.git
$ cd Redmine-docker-with-LDAP
```
1. Modify to your environment

Modify following 2 line in docker-compose.yml as your environment
```
    - SMTP_USER=<MyUserName>
    - SMTP_PASS=<MyPassword>
```

1. Ready to go !

```
$ docker-compose up -d
```

## Access

### Redmine
http://<your machine>/redmine

### php ldap admin
http://<your machine>:18080/



