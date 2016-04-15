# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "dhoppe/ubuntu-12.04.5-amd64"
  #config.vm.box = "geerlingguy/centos7"
    config.ssh.password = "vagrant"
    config.ssh.insert_key = true
    config.vm.network "private_network", ip: "192.168.66.6"
end
