# Khansar Website

Simple HTML website containerized using Docker and Nginx.

## Run locally

Build image

docker build -t khansar-site .

Run container

docker run -p 8080:80 khansar-site

Open in browser

http://localhost:8080
