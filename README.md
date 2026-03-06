#Docker Webserver Projekt

Dieses Projekt zeigt eine einfache statische Website, die mit Docker und Nginx unter Ubuntu bereitgestellt wird.

## Verwendete Technologien
- Ubuntu
- Docker
- Nginx

## Projektinhalt
Eine HTML-Datei wird in ein Nginx-Docker-Image kopiert und anschließend als Container gestartet.

## Build
docker build -t devops-test .

## Start
docker run -p 8080:80 devops-test

##
http://localhost:8080
