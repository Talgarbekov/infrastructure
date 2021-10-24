# Ansible Collection - talgarbekov.infrastructure
> created talgarbekov.infrastructure collection (different versions)
    in order to do that, i have rewatched all of the previous "ansible-videos" to better understand the process.
* versions 1-3 serve as a backup option (for now, but in big companies newer version means never "updated version")
* version number 4 (updated version) - has different roles:
    1. ec2
    2. wordpress (on ubuntu services)
    3. group
    4. iam user

tips:
    * wordpress (with the help of google): 
        you can install WordPress by using the LAMP (Linux, Apache, MySQL, and PHP) stack to fully control the backend.
    * ec2 - main.yml file contains 5 instances
    * one role to create AWS IAM user and "DevOps" group 
	* one role to create 5 instances. - done
	* one role to install wordpress on ubuntu instances. 