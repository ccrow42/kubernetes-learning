# Kubernetes Learning

Welcome to the kubernetes learning github repository.

I'm going to keep my lesson plan notes, lab notes and any associated commands and yaml files.

This will allow students to copy and paste.

### About the course

This is designed to be an introductory course for traditional systems administrators to start learning the basics of kubernetes. The goal is to be able to have a meaningful conversation with developers and kubernetes administrators.

I would love feedback from actual developers and kubernetes admins.

The labs are designed for ubuntu 18.04. It assumes:
* iSCSI is configured
* You have access to a non-production pure flasharray
* you have API keys to the flash flasharray
* you have a github and dockerhub account

Each lesson will have its own folder in github with the instructor notes, lab notes and additional files

## Syllabus

### Pre work

* Please sign up for a github.com account and a hub.docker.com account.
*Ensure that you can log in to your VM. You will need to be connected to the VPN and have an assigned IP address.
* Be familiar with basic linux command line syntax.



### Lesson 1 - Container Basics
Talk through containers. Why do we like them? What are their limitations.

### Lab 1 - Orientation and SSH keys

### Lesson 2 - Docker vs Kubernetes
How does Kubernetes relate to docker? What problems does kubernetes solve?

### Lab - Docker run and Docker compose
Run our first application: The pure swagger interface! Create our first docker image: An FTP server

### Lesson 3 - The basics of Kubernetes
The parts of a basic kubernetes setup. Pods, Deployments, Services, Ingresses and load balancers.

### Lab - Kubespray
Install kubernetes using kubespray

### Lesson 4 - My first app
Explore how the parts of a simple application relate to eachother

### Lab - Pods, deployments, and services
Deploy the pure swagger interface.

### Lesson 5 - Storage
Overview of PVs and PVCs

### Lab - PVs and PVCs, Minio deployment

### Lesson 6 - PSO and PSO explorer

### Lab - PVCs with PSO

### Lesson 7 - Portworx

###Lab - Introduction to portworx

###Lesson 8 - Networking and Service mesh

###Lab - Networking using DNS and Stateful sets

### 3 Lesson 9 - Advanced kubernetes administration for beginners

### Lab - TBD

### Ending virtual happy hour and open discussion
