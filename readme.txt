vagrant up

vagrant ssh docker-vm
> curl -fsSL get.docker.com -o get-docker.sh && sh get-docker.sh
> sudo usermod -a -G docker $USER
> sudo docker run hello-world

To login with winscp, use 'Allow Key Forwarding' and add the private key file that was provided by vagrant:
When doing that, it will first be converted to a putty key with .ppk extention. Use that key.
D:\vagrant\myDocker\.vagrant\machines\docker-vm\virtualbox\private_key.ppk

