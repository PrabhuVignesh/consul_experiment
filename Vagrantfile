
# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"


  config.vm.define "n1" do |n1|
      n1.vm.hostname = "n1"
      n1.vm.network "private_network", ip: "172.28.128.10"
  end

  config.vm.define "n2" do |n2|
      n2.vm.hostname = "n2"
      n2.vm.network "private_network", ip: "172.28.128.11"
  end

  config.vm.define "n3" do |n3|
      n2.vm.hostname = "n3"
      n2.vm.network "private_network", ip: "172.28.128.12"
  end

  config.vm.define "n4" do |n4|
      n2.vm.hostname = "n4"
      n2.vm.network "private_network", ip: "172.28.128.13"
  end

  config.vm.define "n5" do |n5|
      n2.vm.hostname = "n5"
      n2.vm.network "private_network", ip: "172.28.128.14"
  end
end