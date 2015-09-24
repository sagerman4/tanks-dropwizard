# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "centos67-java8"
  config.vm.box_url = "file:///C:/Users/IBM_ADMIN/Projects/nodeServiceJava/centos67-java8.box"
  config.vm.network :forwarded_port, host: 4567, guest: 8080
end
