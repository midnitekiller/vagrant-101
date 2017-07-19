# vagrant-101
Vagrant 101 for dummies

Tools to use:

	* Vagrant version 1.7.4
	* Vagrant Box Precise64
	 	http://files.vagrantup.com/precise64.box
	* Sublime Text 3 as editor (optional)
	* VirtualBox for virtual platform
	* Install git for repository 

Initial Procedures:

	Installing required tools:

		* Install vagrant 1.7.4 on your workstation 
		* Install virtualbox ()
		* Install sublime text 3
		* Install git

	Creating you own ssh-key:

		* unix box command: ssh-keygen -t rsa -C "youremail@here.com")
							change ssh key file permissions to (-rw-r--r--)
		* windows (IDK)


	Configuring tools:

		* Configuring git
			** git config --global user.name "your name here"
			** git config --global user.email "your email here"
		
		* Add your ssh key to your github.com (repo) config for izzi pizzi permissions
		
		* Vagrant configuration
			** add vagrant box command: vagrant box add [options] <name, url, or path> --insecure
			
			-- Later to install vagrant plugins for performance 
				* vagrant cachier
				* vagrant omnibus
				* vagrant berkshelf

	Vagrant production commands:

		* Deploy: 		vagrant up --provision
		* Stop:	  		vagrant halt
		* Destroy:		vagrant destroy
		* box login: 	vagrant ssh (default root user: "vagrant:vagrant")


Team Ramboo "must do" first project:

	## Create a working vaagrant LAMP server with:
		
		1. memory allocation of 512MB 
		2. public network as 33.33.33.33 port: 8080
		3. box hostname as "team-ramboo.feeder"
		4. a synced and functional "php-info.php" file on a designated directory
		5. use any provisioning procedures you feel comfortable
			- shell inline or as script.sh file or as script path
			- chef, puppet, ansible, salt
		6. git installed

	## Commit your work on github as branch as "your name"
 

Contributors: 

	Ramboo.TheSecond
	BrotherOfRamboo


(Feel free to fork and contribute)