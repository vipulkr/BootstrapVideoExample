# Instructions for installing and running this vagrant under Windows #

## Vagrant Installation ##

**note: All installers are available on the file server @ http://172.23.238.13/software/.**

1. Make sure VTx is enabled on your computer.
1. Install virtualbox version 4.3.x.
1. Install Vagrant.
1. Install git bash.

## Running vagrant ##

1. Run the git-bash shell.
1. Pull the source from github - ``` git clone git@github.com:stackroute/vagrant-html-bootstrap.git ```
2. cd into the newly cloned directory.
3. run ``` vagrant up ``` to create or start an instance.
4. run ``` vagrant ssh ``` to enter the vagrant instance.
5. Inside the vagrant box run ``` static /vagrant ``` to start the static webserver. Open the
   url http://127.0.0.1:8080/ in the browser to access server.
6. Open the cloned directory with Atom or Sublime and start coding!!!
