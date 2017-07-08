# vagrant
quickly install vm's with vagrant

copy local ssh key to new vm with ansible playbook

place the playbook in the same dir as the Vagrantfile

make sure your local ssh key which you want to use for ssh is placed in the home dir of the running user, or change the path in the vagrant-provision.yml file

# usage
git clone git://github.com/mxkle/vagrant

cd vs

vagrant up
