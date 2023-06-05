This is a documentation of how to create a vagrant in UBUNTU<br>
Open the Terminal application:
<br>
Now you will execute command line in your Terminal (each of them start with $)
<br>
Install VirtualBox:``` $ sudo apt-get install virtualbox ```
<br>
Install Vagrant:```  $ sudo apt-get install vagrant ```
<br>
Add the Ubuntu 20.04 (Focal) image to your box list:``` $ vagrant box add ubuntu/focal64 ```** Warning: this step can take time **
Many other images are available here <br>
Create your first virtual machine:
``` $ vagrant init ubuntu/focal64 ``` -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine
``` $ vagrant up ``` -> it will start your virtual machine
``` $ vagrant ssh ``` -> now you are inside your virtual machine.