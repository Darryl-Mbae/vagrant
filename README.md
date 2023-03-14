# Vagrant ![image](https://user-images.githubusercontent.com/102142446/225112066-613fe29e-4a24-4ce8-a979-a86dee9f5659.png)

Vagrant is an open-source software product for building and maintaining portable virtual software development environments; e.g., for VirtualBox, KVM, Hyper-V, Docker containers, VMware, Parallels, and AWS.
With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.

## Why Vagrant?
Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

To achieve its magic, Vagrant stands on the shoulders of giants. Machines are provisioned on top of VirtualBox, VMware, AWS, or any other provider. 

### My Understanding 
In my Understanding it is saying goodbye to downloading an ISO file for hours or upto a day you can instantly start using different os terminals in minutes and I will show you how 

## Steps to Installing Vagrant
## Mac OSx
* Download VirtualBox from this [link](https://www.virtualbox.org/wiki/Downloads)
* Install VirtualBox or Virtual machine of your choice ( Here I will be using VirtualBox cause it is more supported)
* Download Vagrant from this [link](https://developer.hashicorp.com/vagrant/downloads)
* Install Vagrant
* Open the Terminal application

Now you will execute command line in your Terminal (each of them start with $)
* Add the Ubuntu 20.04 (Focal) image to your box list: 
```$ vagrant box add ubuntu/focal64```
Warning: this step can take time
* Create your first virtual machine:
```$ vagrant init ubuntu/focal64```  -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine
