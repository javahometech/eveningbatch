Vagrant.configure("2") do |config|
  config.vm.define "node1" do |node1|
    node1.vm.box = "bento/centos-7.2"
    node1.vm.network "private_network", ip: "192.168.50.70"
  end

  config.vm.define "node2" do |node2|
    node2.vm.box = "bento/centos-7.2"
    node2.vm.network "private_network", ip: "192.168.50.80"
  end
end
