### Start kafka cluster
```
docker-compose up -d
```
---

kcat
```bash

kcat -L -b localhost:39092
kcat -P -b localhost:39092 -t mail 
kcat -C -b localhost:39092 -t mail 


```