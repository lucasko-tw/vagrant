# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.box = "esss/centos-7.1-desktop"
  config.vm.network "private_network", :type => 'dhcp', :adapter => 2
  config.vm.network "forwarded_port", host: 80 , guest: 8080 
   
  config.vm.provider "virtualbox" do |vbox|
    vbox.name = "My CentOS 7"
    vbox.memory = 2048
    vbox.cpus = 2

  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end


end
