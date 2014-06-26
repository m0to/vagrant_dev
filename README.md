vagrant_dev
===========

Vagrant development box for Rails, Mongo &amp; Node


To get the symlinks to work.
vagrant ssh
sudo mkdir /workplace
sudo nano /etc/fstab
Add '/host /workplace none bind'
sudo mount /workplace

At some point I'll add this into the vagrantfile
