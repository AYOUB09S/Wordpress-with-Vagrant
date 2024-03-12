# Wordpress-with-Vagrant
This project aims to facilitate the deployment of a robust and highly available WordPress application through Vagrant. The architecture includes key components such as Apache as the load balancer, two WordPress applications (wordpress-1 and wordpress-2), an NFS Share named "nfs," and a MySQL Database labeled "mysql
WordPress with Vagrant Stack

The objective of this project is to deploy a highly available WordPress application using Vagrant.

# The application stack consists of:

Load Balancer: Apache
WordPress Applications:
wordpress-1
wordpress-2
NFS Share: nfs
MySQL Database: mysql

The two WordPress applications will mount the WordPress folder into the following path: /opt/wordpress.

The WordPress folders are located on the NFS Share at the location: /mnt/wordpress.

# Components:

MySQL
Apache
NFS Share
WordPress
