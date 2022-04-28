# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"
  #obs.: necessário ter o plugin vagrant-disksize
  #usar o comando: vagrant plugin install vagrant-disksize
  config.disksize.size = '20GB' #só é possível aumentar o armazenamento, e não diminuir os 40 GB padrões :(#
  config.vm.provider "virtualbox" do |vb|
	vb.memory = "2048"
	vb.name = "teste-superset"
	vb.cpus = 2 #no de cpus	
	
   end
   
   config.vm.network "private_network", ip: "192.168.33.10"

end
