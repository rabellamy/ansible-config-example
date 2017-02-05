VAGRANTFILE_API_VERSION = '2'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = 'ubuntu/trusty64'

  config.ssh.forward_agent = true

  # Ansible for provisioning.
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisioning/main.yml"
    ansible.sudo = true
  end
end
