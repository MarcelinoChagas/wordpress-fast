Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.hostname = "wordpress"
  config.vm.network "public_network"
  config.vm.provision "shell", path: "provision.sh"
end
