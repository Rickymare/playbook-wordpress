Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/trusty64"
    config.vm.hostname = "wordpress"
    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "deploy.yml"
    end
end
