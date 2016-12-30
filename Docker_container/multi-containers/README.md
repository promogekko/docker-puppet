Install docker-compose on the host 

yum install python-pip

hit 
pip install docker-compose

To build/start both container master and slave

Type 
docker-compose up -d 
-d means containers are both detached, run in background

Sanity test hit
docker-compose ps

