Vagrant.configure("2") do |config|
  config.vm.define "vagrant_1" do |v1|
    v1.vm.box = "ubuntu/bionic64"
    v1.vm.network "private_network", ip: "172.30.1.5"
    v1.vm.provision "shell", inline: "echo \"ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDDKjmhrNpfST5wfDeFjawq2pZrLuJfAb6uqzq037ERIX/eaz88SPk5E621rkO4gHueYUzFj+oTrikFH2RfCldXOzkuyNoqOQJkOCA9LsSS6D5ZOPle+oeruqIjL+DEdJJyauMfuamYMVK/FuE4uLernY7o2GfilPpthf3/6sdhqqGkVdSUmb4/6wA8H9p+Lhp1GwCDzMa3+KL9cGL5vzNCvC6sJrjtMd50mboem/p7fuveFNZVXuVrrnKW+z1srA2Bt5GHnWq4MxqX0YsE/7BLaaeEz+jcGxWywSk3gMUfi9srBej7V7ieEtfAaB1kOMA55p/n4EesjqJ58Mi19UMX cyrus@hestia.lan\" >> .ssh/authorized_keys"
  end

  config.vm.define "vagrant_2" do |v2|
    v2.vm.box = "ubuntu/bionic64"
    v2.vm.network "private_network", ip: "172.30.1.6"
    v2.vm.provision "shell", inline: "echo \"ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDDKjmhrNpfST5wfDeFjawq2pZrLuJfAb6uqzq037ERIX/eaz88SPk5E621rkO4gHueYUzFj+oTrikFH2RfCldXOzkuyNoqOQJkOCA9LsSS6D5ZOPle+oeruqIjL+DEdJJyauMfuamYMVK/FuE4uLernY7o2GfilPpthf3/6sdhqqGkVdSUmb4/6wA8H9p+Lhp1GwCDzMa3+KL9cGL5vzNCvC6sJrjtMd50mboem/p7fuveFNZVXuVrrnKW+z1srA2Bt5GHnWq4MxqX0YsE/7BLaaeEz+jcGxWywSk3gMUfi9srBej7V7ieEtfAaB1kOMA55p/n4EesjqJ58Mi19UMX cyrus@hestia.lan\" >> .ssh/authorized_keys"
  end
end
