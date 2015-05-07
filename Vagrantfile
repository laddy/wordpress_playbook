Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provider "virtualbox" do |v|
    v.customize ["modifyvm", :id, "--ostype", "Ubuntu_64"]
    v.name = "Vagrant Ubuntu14.04"
    v.cpus = 1
    v.memory = 1024
  end
  config.vm.network "private_network", ip: "192.168.33.11"
end
