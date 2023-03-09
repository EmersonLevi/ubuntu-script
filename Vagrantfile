Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/focal64"
  config.vm.network "public_network"
  config.vm.provision "shell", path: 'script.sh'

  
  config.vm.provider "virtualbox" do |vb|
    vb.name = 'ubuntu-script'
    vb.memory = "1024"
    vb.cpus = '1'
   end

end
