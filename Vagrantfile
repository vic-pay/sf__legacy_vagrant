Vagrant.configure("2") do |config|
  config.vm.hostname = "legacy-pg"
  config.vm.box = "capensis/ubuntu20.04"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisioning/playbook.yml"
  end
end
