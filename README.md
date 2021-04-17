```sh
http -v --json POST localhost:8080/login username=admin password=admin
```
```sh
http -f GET localhost:8080/auth/hello "Authorization:Bearer XXXXXX"  "Content-Type: application/json"
```
```sh
http -f GET localhost:8080/api/v1/accounts "Authorization:Bearer XXXXXX"  "Content-Type: application/json"
```