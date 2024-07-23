# PHP with Docker

## Get Started

### 1. Image Build
```
docker build -t php:0.1 .
```

### 2. Image Build
```
docker run -d -p 80:80 -v ./src:/var/www/html -v ./logs:/var/log/apache2 --name php php:0.1
```