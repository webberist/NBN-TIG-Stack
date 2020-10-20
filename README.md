# NBN-TIG-Stack Lite
A docker compose for NBN Users to make a TIG stack.

## Usage Guide

#### TODO finish documentation

1. Install Docker
   - [Debain](https://docs.docker.com/engine/install/debian/)
   - [CentOS](https://docs.docker.com/engine/install/centos/)
   - [Fedora](https://docs.docker.com/engine/install/fedora/)
   - [MacOS](https://docs.docker.com/docker-for-mac/install/)
   - [Windows](https://docs.docker.com/docker-for-windows/install/)
2. Download and extract the Repository eg: `wget https://github.com/ChrisRiddell/NBN-TIG-Stack/archive/lite.zip && unzip lite.zip`
3. Edit `./configuration.env`
4. Change to the NBN-TIG-Stack-lite directory in a shell/terminal eg: `cd NBN-TIG-Stack-lite`
5. Run the following commands
   - `docker-compose build`
   - `docker-compose pull`
   - `docker-compose up -d`
6. In a browser go to *(replacing [ip] with the computer/server/rpi's IP address)* `http://[ip]:3000/`
7. Login with username admin password admin and change the password when prompted
