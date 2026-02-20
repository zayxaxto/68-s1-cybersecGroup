# Cyber Security

## Members

| Student ID | Name | Nickname |
| :--- | :--- | :--- |
| 6602041620122 | Phakkhaphon Phueakdet | Auto |
| 6602041630012 | Kanokwan Chaichana | Mail |
| 6602041610101 | Khongdech Mee-intha | Tong |
| 6602041620114 | Puttipong Joywong | Mic |

## Environment
``` 
cp env.simple .env
```
## Running a Service
### Database
```

docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d #background
```

### Admin
```
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d #background
```

### App 
```
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```

## Running 3 services in one line (etg.Database, PG Admin, Strapi)
```
docker-compose up #monotoring
docker-compose up -d #background daemon
```