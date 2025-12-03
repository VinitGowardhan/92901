
Vagrant.configure("2") do |config|
 config.vm.box = "bento/ubuntu-24.04"
 
 config.vm.define "controller" do |c|
 c.vm.hostname = "controller"
 c.vm.network "private_network", ip: "192.168.56.10"
 end

 config.vm.define "target1" do |t|
 t.vm.hostname = "target1"
 t.vm.network "private_network", ip: "192.168.56.20"
 end

end
