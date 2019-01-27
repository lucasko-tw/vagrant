### Vagrant Up

```sh
MacBook-Pro-2:windows-10 lucasko$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'Microsoft/EdgeOnWindows10'...
==> default: Matching MAC address for NAT networking...
==> default: Setting the name of the VM: windows-10_default_1548626484834_17977
==> default: Fixed port collision for 22 => 2222. Now on port 2200.
==> default: Vagrant has detected a configuration issue which exposes a
==> default: vulnerability with the installed version of VirtualBox. The
==> default: current guest is configured to use an E1000 NIC type for a
==> default: network adapter which is vulnerable in this version of VirtualBox.
==> default: Ensure the guest is trusted to use this configuration or update
==> default: the NIC type using one of the methods below:
==> default: 
==> default:   https://www.vagrantup.com/docs/virtualbox/configuration.html#default-nic-type
==> default:   https://www.vagrantup.com/docs/virtualbox/networking.html#virtualbox-nic-type
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2200 (host) (adapter 1)
==> default: Running 'pre-boot' VM customizations...
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2200
    default: SSH username: IEUser
    default: SSH auth method: password
    default: Warning: Connection reset. Retrying...
    default: Warning: Remote connection disconnect. Retrying...
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default: 
    default: Guest Additions Version: 5.0.2
    default: VirtualBox Version: 5.2
==> default: Mounting shared folders...
    default: /vagrant => /Users/lucasko/Downloads/vagrant/windows-10
MacBook-Pro-2:windows-10 lucasko$ vagrant destroy
    default: Are you sure you want to destroy the 'default' VM? [y/N] y
==> default: Forcing shutdown of VM...
==> default: Destroying VM and associated drives...
MacBook-Pro-2:windows-10 lucasko$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'Microsoft/EdgeOnWindows10'...
==> default: Matching MAC address for NAT networking...
==> default: Setting the name of the VM: windows-10_default_1548626721854_59774
==> default: Fixed port collision for 22 => 2222. Now on port 2200.
==> default: Vagrant has detected a configuration issue which exposes a
==> default: vulnerability with the installed version of VirtualBox. The
==> default: current guest is configured to use an E1000 NIC type for a
==> default: network adapter which is vulnerable in this version of VirtualBox.
==> default: Ensure the guest is trusted to use this configuration or update
==> default: the NIC type using one of the methods below:
==> default: 
==> default:   https://www.vagrantup.com/docs/virtualbox/configuration.html#default-nic-type
==> default:   https://www.vagrantup.com/docs/virtualbox/networking.html#virtualbox-nic-type
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2200 (host) (adapter 1)
==> default: Running 'pre-boot' VM customizations...
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2200
    default: SSH username: IEUser
    default: SSH auth method: password
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default: 
    default: Guest Additions Version: 5.0.2
    default: VirtualBox Version: 5.2
==> default: Mounting shared folders...
    default: /vagrant => /Users/lucasko/Downloads/vagrant/windows-10
==> default: Running provisioner: file...
MacBook-Pro-2:windows-10 lucasko$ 
  [Restored 27 Jan 2019 at 22:19:55
```


### IE Download Links

* [IE 8](https://download.microsoft.com/download/F/8/8/F88F09A2-A315-44C0-848E-48476A9E1577/IE8-WindowsVista-x86-ENU.exe)
* [IE 9](https://download.microsoft.com/download/0/8/7/08768091-35BC-48E0-9F7F-B9802A0EE2D6/IE9-WindowsVista-x86-enu.exe)
* [IE 10](https://download.microsoft.com/download/A/F/7/AF7B74FB-A4C9-4B28-AFD9-77CB9B85F62A/EIE11_EN-GB_MCM_WIN764.EXE)

