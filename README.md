1. Download and install VirtualBox and Vagrant
2. Run VirtualBox

3. From the terminal, inside the cloned repository, run the following command to initialise vagrant:
    vagrant init ubuntu/xenial64

4. Next, install the hosts updater plugin by running:
    vagrant plugin install vagrant-hostsupdater

5. Start the server:
    vagrant up

6. Move into the virtual machine:
    vagrant ssh

7. Inside the VM, update by running:
    sudo apt-get update -y

8. Run the following to install nginx:
    sudo install nginx -y
