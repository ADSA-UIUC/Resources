# Vagrant

1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html).
![Vagrant Download for Mac](/images/dev-environment/vagrant/vagrant-windows-download.png?raw=true)

2. Download and install [Virtualbox](https://www.virtualbox.org/wiki/Downloads).
![Virtualbox Download for Mac](/images/dev-environment/vagrant/virtualbox-windows-download.png?raw=true)

3. Download the vagrant box you want to use
![Releases Tab](/images/dev-environment/vagrant/github-releases-tab.png?raw=true)
![Download](/images/dev-environment/vagrant/github-releases-download.png?raw=true)

4. Install [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html).
![Putty Download](/images/dev-environment/vagrant/putty-download.png?raw=true)

5. Change directory to the location of the box that you downloaded
![Change Dir](/images/dev-environment/vagrant/change-dir-windows.png?raw=true)

6. Add the box to vagrant your local vagrant in your terminal
![Vagrant Add](/images/dev-environment/vagrant/vagrant-add-windows.png?raw=true)

7. Open a terminal (cmd.exe) and run boot the vagrant environment
![Vagrant up](/images/dev-environment/vagrant/vagrant-up-windows.png?raw=true)


8. Login to the vagrant box

![Windows SSH](/images/dev-environment/vagrant/putty-ssh.png?raw=true)

 - Connect edit the connection with
  - Hostname: 127.0.0.1
  - Port: 2222
  - Connection Type: ssh
  - Username: vagrant
  - Password: vagrant

When you are logged in, you should see this:
![Windows logged in](/images/dev-environment/vagrant/windows-login.png?raw=true)

This will log you in to the virtual machine and give you console access. 

