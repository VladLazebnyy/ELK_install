Vagrant.configure(2) do |config|

  #logstash noeds start
  config.vm.define "logstash0" do |logstash0|
    config.vm.hostname = "ubuntu.logstash0"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end

  config.vm.define "logstash1" do |logstash1|
    config.vm.hostname = "ubuntu.logstash1"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end
  #ES nodes start
  config.vm.define "ES0" do |ES0|
    config.vm.hostname = "ubuntu.ES0"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
  		v.memory = 1024
	  end
  end

  config.vm.define "ES1" do |ES1|
    config.vm.hostname = "ubuntu.ES1"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end

  config.vm.define "ES2" do |ES2|
    config.vm.hostname = "ubuntu.ES2"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end

#Kibana node start
config.vm.define "Kibana" do |Kibana|
  config.vm.hostname = "ubuntu.Kibana"
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :private_network, type: "dhcp"
  config.vm.boot_timeout = 240

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end
end
end
