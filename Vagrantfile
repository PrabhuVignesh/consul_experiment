
# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_check_update = false
  
  config.vm.define "n1" do |n1|
      n1.vm.hostname = "n1"
      n1.vm.network "private_network", ip: "172.28.128.10"
      n1.vm.provider :virtualbox do |vb|
          vb.memory = "256"
      end
  end

  config.vm.define "n2" do |n2|
      n2.vm.hostname = "n2"
      n2.vm.network "private_network", ip: "172.28.128.11"
      n2.vm.provider :virtualbox do |vb|
          vb.memory = "256"
      end
  end

  config.vm.define "n3" do |n3|
      n3.vm.hostname = "n3"
      n3.vm.network "private_network", ip: "172.28.128.12"
      n3.vm.provider :virtualbox do |vb|
          vb.memory = "256"
      end
  end

  config.vm.define "n4" do |n4|
      n4.vm.hostname = "n4"
      n4.vm.network "private_network", ip: "172.28.128.13"
      n4.vm.provider :virtualbox do |vb|
          vb.memory = "256"
      end
  end

  config.vm.define "n5" do |n5|
      n5.vm.hostname = "n5"
      n5.vm.network "private_network", ip: "172.28.128.14"
      n5.vm.provider :virtualbox do |vb|
          vb.memory = "256"
      end
  end
end