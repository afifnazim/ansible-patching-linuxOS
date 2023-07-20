# ansible-patching-linuxOS
Documenting the process of patching linux OS using ansible and automating the task.


The tasks which needs to be performed everyday or on a regular basis should be automated. By doing that we can save time for other important tasks.

Linux Server Patching is one of those tasks which a System Administrators or DevOps Engineers does on a regular basis on onprem servers, cloud or on the virtualized servers.

By using ansible we can seamlessly make the updates without even loggin in to the remote servers. 

Main focus of this repository would be - 

- Kernel Patching on Linux servers
- Upgrading all the installed packages on CentOS / RHEL servers

I've added the main.yml file, which includes the playbook required to update the OS and check if reboot is required. It will check and reboot the remote server if kernel has been upgraded.

Also created a hosts file, which will be used to store the credentials used to access remote servers and make groups of servers that needs to be patched. 
