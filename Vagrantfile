CPUS="1"
MEMORY="1024"

Vagrant.configure("2") do |config|
  config.vm.box = "mediaos/centos7-python"
  config.vm.box_version = "0.1.2"
  config.vm.hostname = "master.ansible.vm"

  config.vm.provider "virtualbox" do |v|
    v.name = "master.ansible.vm"
    v.memory = MEMORY
    v.cpus = CPUS
  end
end
