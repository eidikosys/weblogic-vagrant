# weblogic-vagrant

Steps to setup vagrant environment for running automated weblogic installation scripts

Step 1: Download and install latest version of Vagrant.

Step 2: Download and install latest version of VirtualBox.

Step 3: Download base box(centos-7-1511-x86_64) from https://dl.dropboxusercontent.com/s/filvjntyct1wuxe/centos-7-1511-x86_64.box

Step 4: Add downloaded box(centos-7-1511-x86_64) to Vagrant by using below command
       Vagrant box add centos-7-1511-x86_64 /localtion/centos-7-1511-x86_64.box
       
Step 5: Download/clone welogic-vagrant repository.

Step 6: cd weblogic-vagrant repository.

Step 7:Include below list of softwares in the /weblogic-vagrant/software folder
			1) fmw_12.2.1.2.0_wls.jar
			2) jce_policy-8.zip
			3) jdk-7u40-linux-x64.tar.gz
			4) jdk-8u72-linux-x64.tar.gz
			
Step 8: Boot and install weblogic by simply running  below vagrant commad
         Vagrant up admin
	 
Step 9: Now access your weblogic12c Admin console at https://10.10.10.10:7002/console or at http://10.10.10.10:7001/console

Thanks
Tirapa Reddy Tondapu
		
