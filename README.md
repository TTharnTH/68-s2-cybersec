# Cyber Security

## Information
* ###### Phuthan Aendu
* 6702041510148
* s6702041510148@email.kmutnb.ac.th

## Environment
```sh
cp env.simple env
```

## Running Service
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```
### Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```
### App
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # background
```