## Vagrant commands
There are several Vagrant commands which you can use to control your box.

Some of the important ones are:

* ```vagrant up``` Bring a box online.
* ```vagrant status``` Show current box status.
* ```vagrant suspend``` Pause the current box
* ```vagrant resume``` Resume the current box.
* ```vagrant halt``` Shutdown the current box.
* ```vagrant destroy``` Destroy the current box. By running this command, you will lose any data stored on the box.
* ```vagrant snapshot``` Take a snapshot of the current box.
* ```vagrant box add ADDRESS```  This adds a box with the given address to Vagrant. The address can be one of three things:
> A shorthand name from the public catalog of available Vagrant images, such as "hashicorp/bionic64".
> File path or HTTP URL to a box in a catalog. For HTTP, basic authentication is supported and http_proxy environmental variables are respected. HTTPS is also supported.
> URL directly a box file. In this case, you must specify a --name flag (see below) and versioning/updates will not work.
* ```vagrant box list``` This command lists all the boxes that are installed into Vagrant.
