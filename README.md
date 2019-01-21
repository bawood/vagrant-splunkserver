# vagrant-splunkserver Vagrant/Ansible to setup quick Splunk server for testing development
1. Install Dependencies:
  * git - https://git-scm.com/downloads
  * Oracle VirtualBox - https://www.virtualbox.org/wiki/Downloads
  * Vagrant - https://www.vagrantup.com/downloads.html
  * vagrant-vbguest - https://github.com/dotless-de/vagrant-vbguest
  * Ansible - http://docs.ansible.com/ansible/latest/intro_installation.html#installing-the-control-machine
  2. ```git clone https://github.com/bawood/vagrant-splunkserver```
  3. edit password field in vagrant-splunkserver/provisioning/files/user-seed.conf and then  
    ```cd vagrant-splunkserver && vagrant up```
  4. wait & then point your browser at http://localhost:8088
