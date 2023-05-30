# nifi-cluster

თუ არ გიყენიათ დოკერი, ინსტრუქცია იხილეთ ამ ლინკზე https://docs.docker.com/engine/install/ubuntu/

sudo apt install docker-compose -y


sudo git clone https://github.com/systemctl-reload/nifi-cluster.git

cd nifi-cluster 

შევქმნათ ნეტვორკი დოკერში: nifinet

sudo docker network create -d bridge nifinet

გავუშვათ კონტეინერები
sudo docker-compose up -d
