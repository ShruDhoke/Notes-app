# Simple Notes App
This is a simple notes app built with React and Django.

# Guide for the project check blog: 
  https://tech-shrutii.blogspot.com/p/nginx.html
## Requirements
1. Python 
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/ShruDhoke/Notes-app.git
```
2. Build the app
```
docker build -t notes-app .
```
3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx
Install Nginx reverse proxy to make this application available

```
sudo apt-get update sudo apt install nginx
```
## Output
![image](https://github.com/ShruDhoke/Notes-app/assets/114598355/178b840d-9128-4769-a589-0255bbe41bad)


