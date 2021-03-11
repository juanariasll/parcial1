# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
config.vm.define :servidor do |servidor|
servidor.vm.box = "bento/centos-7.9"
servidor.vm.network :private_network, ip: "192.168.50.4",
virtualbox_intnet:"lan1"
servidor.vm.hostname = "servidorPXE"
end
end
