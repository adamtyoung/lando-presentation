##  Vagrant vs Docker

Problems with Vagrant:
* uses a lot of your machine's resources to build full VM with Virtualbox
* requires a lot of synergy between Ansible, Vagrant, and local scripts
* disconnect between local environment and container (```vagrant ssh```)
* hard to get running properly and overkill for most things
