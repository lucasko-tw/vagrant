### Install vagrant on Mac

```sh
brew cask install vagrant
```

### Download box from internet

```
vagrant box add {title} {url}

vagrant init {title}

vagrant up
```

> vagrant box add centos7 https://github.com/tommy-muehle/puppet-vagrant-boxes/releases/download/1.1.0/centos-7.0-x86_64.box



### Vagrantfile

```sh
Vagrant.configure("2") do |config|
 
  # Desktop version of CentOS 7
  config.vm.box = "esss/centos-7.1-desktop"
  
  # Host-Only Adapter
  config.vm.network "private_network", :type => 'dhcp', :name => 'vboxnet0', :adapter => 2
    
  config.vm.provider "virtualbox" do |vbox|
    vbox.name = "My CentOS 7"
    vbox.memory = 2048
    vbox.cpus = 2
  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end

```

### Run
```
vagrant up
```

### Reload
```
vagrant reload
```

### SSH
```
vagrant ssh
```

### Install Ansible on Host

```
sudo easy_install pip
sudo pip install ansible --quiet
```


### Apply Povision

```
vagrant provision
```