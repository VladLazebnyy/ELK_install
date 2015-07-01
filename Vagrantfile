Vagrant.configure(2) do |config|

  #logstash noeds start
  config.vm.define "ELK" do |ELK|
    config.vm.hostname = "ubuntu.ELK"
    config.vm.box = "ubuntu/trusty64"
    config.vm.network :private_network, type: "dhcp"
    config.vm.boot_timeout = 240

    config.vm.provider "virtualbox" do |v|
      v.memory = 1024
    end
  end
end
