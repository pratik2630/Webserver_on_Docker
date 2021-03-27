# Webserver_on_Docker
An Ansible PlayBook that does the  following operations in the managed nodes: 🔹 Configure Docker 🔹 Start and enable Docker services 🔹 Pull the httpd server image from the Docker Hub 🔹 Run the docker container and expose it to the public 🔹 Copy the html code in /var/www/html directory and start the web server 


Apply this playbook on your ansible master node. Configure ansible.cfg file and upload ip's in inventory file. This playbook will run on all ip's or you can change ip group in inventory and update in code.

To run this playbook just run "ansible-playbook dockerServer.yml"
