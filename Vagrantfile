# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://vagrantcloud.com/search.
  config.vm.box = "ubuntu/xenial64"
  
  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 4
  end
  
  # public network => bridged
  config.vm.network "public_network"
  
  # install and configure software
  # config.vm.provision :shell, :path => "bootstrap.sh"
  config.vm.synced_folder "C:/Users/Jiri/Documents/development/flask_project", "/vagrant"

end
