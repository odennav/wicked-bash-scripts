Vagrant.configure("2") do |config|

  config.vm.define "cool" do |cool|
      cool.vm.box = "bento/ubuntu-22.04"
      cool.vm.network "private_network", ip: "192.168.xx.xx"
      cool.vm.hostname = "cool"
      cool.vm.synced_folder "C:/Linux and Unix Bash Scripts", "/vagrant_data"
      #cool.vm.provision :shell, :inline => "sudo sed -i 's/PasswordAuthentication no/PasswordAuthentication yes/g' /etc/ssh/sshd_config; sudo systemctl restart sshd;", run: "always"
      cool.vm.provider "virtualbox" do |vb|
          vb.memory = "2048"
          vb.name = "cool"
      end
  end

end
