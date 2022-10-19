# **Docker Tutorial for Beginners**
## **Life Before Docker** 
#### You can run multiple applications on same server, either by using Virtual Machines, but the problem arised is we had to create different VM and different OS for all the applications assigning some Memory and much more. 

## **What is Virtual Machine & Containers** 
## **Virtual Machine**
#### It runs on top of an emulating software called the hypervisor which sit between the hardware and the virtual machine. The hypervisor is the key to enable virtualization. It manages the sharing of physical resources into virtual machines. Each virtual machine runs its own guest operating system. They are less agile and have low portability than containers.

## **Containers**
#### It sits on the top of a physical server and its host operating system. They share a common operating system that requires care and feeding for bug fixes and patches. They are more agile and have high portability than virtual machines.

### **This is the site in order to Know more about [Container and Virtual Machines](https://www.geeksforgeeks.org/difference-between-virtual-machines-and-containers/)**

## **What is an Hypervisor**
#### It is used to create multiple machines on a host operating Systems and it manages virtual Machine. 

## **Difference between Virtual Machines and Containers**
#### Some of the differences are as follows :

### **Virtual machines**                                
#### 1. They have their own operating system and do not use the host's Operating systems.
#### 2. They have their own space allocated 
#### 3. VM is hardware virtualizations
#### 4. Virtualization is the creation of a virtual version of something such as an operating systems, server or a storage device or network resources. 

### **Containerization**
#### 1. Containerization is an effectively method for deploying applications. 
#### 2. It container encapsulates an application with its own operating 

## **What is Docker?**
#### Docker is container platform that allows you to build, test and deploy applications quickly. A developer defines all the applications and its dependencies in a Dockerfile which is then used to build Docker Images that defines a Docker container. Doing this ensures that your application will run in any environment

## **Why Docker is Used ?**

#### Using docker can help you ship your code faster, gives you control over your applications. You can deploy applications on containers that makes it easier for them to be deployed, scaled, perform rollbacks and identify issues. It also helps in saving money by utlizing resources. Docker-based applications can be seamlessly moved from development machines to production deployments. We can use docker for Microservices, Data Processing, Continuous Integration and Delivery, Containers as a service. 







