# Instructions for installing and running this vagrant under Ubuntu #

## Vagrant Installation ##

1. Install virtualbox - ``` sudo aptitude install virtualbox ```
2. Download the appropriate .deb package (32 or 64 bit) from https://www.vagrantup.com/downloads.html
3. Install with the command - ```sudo dpkg --install vagrant_1.7.4_x86_64.deb```

## Running vagrant ##

1. Pull the source from github - ``` git clone git@github.com:stackroute/vagrant-html-bootstrap.git ```
2. cd into the newly cloned directory.
3. run ``` vagrant up ``` to create or start an instance.
4. run ``` vagrant ssh ``` to enter the vagrant instance.
5. Inside the vagrant box run ``` static /vagrant ``` to start the static webserver. Open the
   url http://127.0.0.1:8080/ in the browser to access server.
6. Open the cloned directory with Atom or Sublime and start coding!!!
