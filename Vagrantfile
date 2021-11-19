Vagrant.configure("2") do |config|

  config.vm.define "m1" do |m1|
    m1.vm.box = "centos/7"
    m1.vm.hostname = "testCentOS"

    config.vm.provider "virtualbox" do |v|
      v.memory = 2048
    end
  end

  config.vm.define "m2" do |m2|
    m2.vm.box = "ubuntu/focal64"
    m2.vm.hostname = "testUbuntu"

    config.vm.provider "virtualbox" do |v|
      v.memory = 2048
    end
  end
end
