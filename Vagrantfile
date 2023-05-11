
Vagrant.configure("2") do |config|

  # configures vm settings
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip:"192.168.0.10"

  # provision the VM to have nginx
  config.vm.provision "shell", path: "provision.sh"

end
