cd docker
sudo docker-compose up -d
cd ../ansible
ansible-playbook -i inventory.yml playbook.yml
