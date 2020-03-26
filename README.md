# docker-compose
Docker-compose sample for django, gunicorn, db and nginx

### Requirement
- Docker Engine >= 1.12.0
- Docker-Compose >= 1.6.0

### Dockerfile 
- ./config/django/Dockerfile-dev : django dockerfile 
- ./config/nginx/Dockerfile-dev : nginx dockerfile

### nginx config
- ./config/nginx/nginx.conf

### docker-compose config
- docker-compose.yml

### Run
- docker-compose up -d

### Check 
- localhost/admin, localhost/hello
