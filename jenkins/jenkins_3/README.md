## **JENKINS TASK 3**

## **1- what is the benefit of using master-slave architecture rather than building on master only ?**


- ### The master-slave architecture provides better scalability, fault tolerance, performance, and flexibility in comparison to depending solely on a single master system as it allows for parallel processing and workload distribution across multiple slave systems and ensures continuity of service even in the presence of failures and offers scalability by allowing additional slave systems to be added as the demand or workload increases.



-----

## **2- what is different between authorization and authentication ?**

- ### Authentication "Who are you?": The process of verifying the identity of a user or entity. It ensures that the individual or system claiming a particular identity is indeed who or what it claims to be

- ### Authorization "What are you allowed to do?" :The process of granting or denying access rights and permissions to authenticated users or entities, that's means the authorization proccess is dependent on the process of authentication

-----

## **3- make jenkins-shared-library and make your jenkinsfile which you used in lab2 to point to this library**
## **The used files can be checked through this [Link.](https://github.com/abdulrahman102/jenkins_2.git)**

- ### Shared library can be used to hold an entire pipeline in declarative method or snippets of reuseable code in the script method, as I go through articles and documents, the declarative method was originally created to be a self contained script with less outsider codes                

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/1.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/2.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/3.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/4.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/5.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/6.png)

-----

## **4- try to make new slave as container or ec2 server and configure master to use it**
- ### After configuring both ec2 instance and jenkins container and adding ssh for both of them, the configuration in the jenkins itself is done by this steps.

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/7.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/8.png) 

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/9.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/10.png)

![](https://github.com/abdulrahman102/Sprints_tasks/blob/master/jenkins/jenkins_3/screenshots/11.png)
