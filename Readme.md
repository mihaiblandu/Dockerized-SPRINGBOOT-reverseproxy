# Spring-Boot App template 
with Docker Compose and Nginx
Reverse Proxy plus Database
#![Deploy](https://miro.medium.com/proxy/1*9hGvYE5jegHm1r_97gH-jQ.png) 
## The challenge
Create a template for development web apps that are deployed on containers.
## The solution
###  in case of windows
#####    1. install chocolate  <? require admin privileges>
         RUN this in powershell or cmd to install Chocolate
```
        Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
#####   2. choco install sudo git docker docker-compose -y
```
        choco install sudo git docker docker-compose -y
```
#####   3. running app
```   
        sudo git clone https://github.com/mihaiblandu/Dockerized-SPRINGBOOT-reverseproxy.git app/
        cd app/
        sudo docker-compose up
```
###  in case of linux or mac
``` 
        sudo git clone https://github.com/mihaiblandu/Dockerized-SPRINGBOOT-reverseproxy.git app/
        cd app/
        sudo docker-compose up
```


# Access http://localhost 
        

    