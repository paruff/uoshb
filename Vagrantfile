Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "curl -sSL https://websploit.org/install.sh | sudo bash"

  config.vm.define "webspliot" do |webspliot|
     webspliot.vm.box = "kalilinux/rolling"
  end

  config.vm.define "vic1" do |vic1|
     vic1.vm.box = "hashicorp/bionic64"
     vic1.vm.box_url = "https://drive.google.com/file/d/1yw0bTcT48Vp59MK0UCyV5iWNEZih6MjJ/view?usp=sharing"
  end
    
  config.vm.define "vic2" do |vic1|
     vic2.vm.box = "hashicorp/bionic64"
     vic2.vm.box_url = "https://drive.google.com/file/d/1lcmnY5A0l8qqpa7D50nWrn_hst_URGic/view?usp=sharing"
  end
end
