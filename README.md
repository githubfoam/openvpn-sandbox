# openvpn-sandbox

Travis (.com) branch:
[![Build Status](https://travis-ci.com/githubfoam/openvpn-sandbox.svg?branch=dev)](https://travis-ci.com/githubfoam/openvpn-sandbox)  

~~~~
>vagrant init --template Vagrantfile.provision.bash.ubuntu.erb
>dir
>vagrant up "kuma-control-plane"
>vagrant up "redis"

>vagrant destroy -f "kuma-control-plane"
>vagrant destroy -f "redis

>vagrant global-status

>del Vagrantfile
>dir
~~~~
