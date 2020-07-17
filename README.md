Install Various Versions of Java 
=========

As the title says, we use this ansible role to ensure Java is installed on a server. This works for Redhat/Centos only. 

Example Playbook:
----------

- hosts: server
  roles:
    - java
      java_packages:
        - java-1.8.0-openjdk
	- java-11-openjdk
       

