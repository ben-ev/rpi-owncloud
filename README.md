# OwnCloud on Docker on a Respberry Pi

This project makes it possible to run OwnCloud on Docker on a Respberry Pi!

You might ask why it's smart to run OwnCloud on Docker, the answer is that it makes it extremely easy to install and remove application on Respberry Pi. When your Docker installation is ready, the only thing you need to do to download, install and start Owncloud is to run this:

Build it:

docker build -t *username*/*imagename* .

where username and imagename can be whatever you want

Run it: docker run -d -i -t -p 443:443 -p 80:80 comzone/rpi-owncloud6


This project is based on https://github.com/comzone/rpi-owncloud, but updated
