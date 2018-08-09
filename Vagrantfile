# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure('2') do |config|
  config.vm.box = 'bento/ubuntu-16.04'
  config.ssh.insert_key = false

  config.vm.provider :virtualbox do |v|
    v.memory = 512
  end

  config.vm.define :web1 do |web1|
    web1.vm.hostname = 'webserver.ersolution.net'
    web1.vm.network :forwarded_port, guest: 80, host: 8080
    web1.vm.network 'private_network', ip: '192.168.50.4'
  end

  config.vm.provision :ansible do |ans|
    ans.playbook = 'provisioning/ansible-playbook.yml'
    ans.ask_vault_pass = true
  end
end
