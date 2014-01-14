ansible-testing
===============

testing ansible for a simple reverse proxy

setup
=====

* sudo easy_install pip
* sudo pip install setuptools --no-use-wheel --upgrade
* sudo pip install virtualenv
* clone repo into <target directory>
* cd into <target directory>
* virtualenv .pythonenv
* source .pythonenv/bin/activate
* pip install ansible
* ansible-playbook reverse-proxy.yml --private-key=/path/to/key.pem -i ./<environment>/inventory

