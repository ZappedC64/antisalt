# antisalt
Ansible roles to stop Salt trojan processes and uninstall the Salt minion on SuSE, Red Hat, and CentOS.

</br>
Command line to use:</br>
</br>
$ ansible-playbook antisalt.yml -k -K -u {username}</br>
</br>
NOTE: You do not need to run the playbook as root and you do not need to specify root as the user name, but the
command line options will prompt you for a sudo password.</br>
</br>
Create a 'hosts' file in the Ansible working directory like this:</br>
</br>
[test01]</br>
server01</br>
server02</br>
server03</br>
</br>
or you can use IP addresses:</br>
</br>
[test02]</br>
10.1.10.31</br>
10.1.10.32</br>
10.1.10.33</br>
</br>
That's it!</br>
/Raj W.</br>
