Vagrant.configure(2) do |config|
  config.vm.hostname = "ubuntu.ES01"
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :private_network, type: "dhcp"
  config.vm.boot_timeout = 240

	config.vm.provider "virtualbox" do |v|
  		v.memory = 1024
	end
end
