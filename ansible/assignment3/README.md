Ansile Assignment-3

Setup an entire infra using ansible playbook on aws

![alt text](pem_key.png)
![alt text](outputVpc.png)
![alt text](outputsubnet.png)
![alt text](outputIG&RT.png)
![alt text](outputSG.png)
![alt text](outputEC2_1st.png)
![alt text](outputEC2_2nd.png)
![alt text](outputEC2_3rd.png)
![alt text](outputEC2_4th.png)
![alt text](outputEC2_5th.png)
![alt text](vpc.png)
![alt text](instance.png)

Setup Spring3HibernateApp (https://github.com/opstree/spring3hibernate) on created infra using ansible playbook by following the below steps:

Install MySQL 

Create the war file for Spring3HibernateApp using maven

Install JDK 11 

Install Tomcat

Send the war file created earlier to path "/opt/tomcat/apache-tomcat-7.0.108/webapps/"
![alt text](loadpage.png)  ![alt text](tomcatweb.png)

Restart tomcat service

opstree/spring3hibernate

A java loaded application for various testing purpose Website
![alt text](spring3hibernatepage.png)

command output
![alt text](commandout.png)