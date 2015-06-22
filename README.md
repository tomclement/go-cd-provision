### GO CD PROVISION

**Description**

Sets up ThoughtWorks GoCD with the following dependencies already installed:

* GIT
* Postgresql
* NodeJS
* XVFB
* Nginx
* Docker
* Ant
* MongoDB
* Selenium Server
* Python, pip and virtualenv
* Google Chrome
* Chromedriver
* PhantomJS

How to use this Repo
--------------

* Add an inventory file
* Run the playbook using the following command:

	```
	ansible-playbook -i [path to inventory] setup.yml
	```

**After successful provisioning:**

* Add an htpasswd file to specify the authentication details
* Edit the Go server XML configuration to suite your preferences