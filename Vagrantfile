# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|

  # Base box related configuration.
  config.vm.box = "ubuntu/trusty32"
  config.vm.box_url = "http://172.23.238.13/vagrant/boxes/trusty-server-cloudimg-i386-vagrant-disk1.box"
  config.vm.box_check_update = false

  # Map the guest os port 8080 to host os port 8080
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  
  # use puppet to provision this virtual box`
  config.vm.provision :puppet do |puppet|
     puppet.manifests_path = "puppet/manifests"
     puppet.module_path = "puppet/modules"
   end
end
