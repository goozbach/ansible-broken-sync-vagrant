Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"

  config.vm.provision :ansible do |ansible|

    ansible.extra_vars = {
        environ: "vagrant",
        ansible_ssh_user: 'vagrant'
    }

    ansible.sudo = true
    ansible.playbook = "site.yml"
  end
end
