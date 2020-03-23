Vagrant.configure("2") do |config|
  
  #configure Debian workstation
  config.vm.define "websrv01" do |websrv01|
  websrv01.vm.box = "debian/jessie64"
  websrv01.vm.hostname = "websrv01"
  websrv01.vm.network "private_network", ip: "192.168.1.10"
    websrv01.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.name = "websrv01"
    end
    websrv01.vm.provision "shell", path: "websrv01.sh"
  end

  #Configure master server
  config.vm.define "master" do |master|
    master.vm.box = "debian/jessie64"
    master.vm.hostname = "master"
      master.vm.network "private_network", ip: "192.168.1.20"
      master.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        vb.name = "master"
      end
      master.vm.provision "shell", path: "master.sh"
  end

  #configure ubuntu webserver
  config.vm.define "web01" do |web01|
    web01.vm.box = "ubuntu/xenial64"
    web01.vm.hostname = "web01"
    web01.vm.network "private_network", ip: "192.168.1.30"
      web01.vm.network "forwarded_port", guest:80, host:8080, auto_correct: true
      web01.vm.network "forwarded_port", guest:443, host:4343, auto_correct: true
      web01.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        vb.name = "web01"
      end
      web01.vm.provision "shell", path: "web01.sh"
  end

  #Configure db server
  config.vm.define "db01" do |db01|
    db01.vm.box = "debian/jessie64"
    db01.vm.hostname = "db01"
    db01.vm.network "private_network", ip: "192.168.1.40"
      db01.vm.network "forwarded_port", guest:3306, host:3306, auto_correct: true
      db01.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        vb.name = "db01"
      end
      db01.vm.provision "shell", path: "db01.sh"
  end
end