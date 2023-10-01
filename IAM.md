# <ins>Creating IAM user using AWS management console<ins>

* ##### This tutorial demonstrates creating a new IAM user with adminstrator access using AWS management console

* ##### You need to login as a root user to the management console to create an IAM user

#### <ins>Create user<ins>

* 1-> Select the IAM 

![alt text](1.png)

* 2-> Click on users

![alt text](2.png)

* 3-> Click on Create User

![alt text](3.png)

* 4->Give an user name

![alt text](4.png)

* 5->Select Attach policies directly

![alt text](6.png)

* 6->Select Adminstrator access

* 7->Select Create User

![alt text](7.png)

* ##### Now you can see a user has been created with the name test-user

#### <ins>Create user group<ins>

* ##### This tutorial demonstrates creating user group using AWS management console

* 1-> Select the users

![alt text](9.png)

* 2-> Select Create group

![alt text](10.png)

* 3-> Create a group name

![alt text](11.png)

* 4-> Select the type of access

![alt text](12.png)

* ##### Now you can see a user has been created with the name test-grp

![alt text](13.png)

* ##### <ins>Adding an user to user group that we created or existing user groups<ins>

* 1-> Select the group name


![alt text](13-1.png)

* 2-> Select Add users

![alt text](14.png)

* 3-> Select the users you want to Add

![alt text](15.png)

* 4-> Add Users

![alt text](16.png)

* ##### <ins>Creating a IAM  Role using console<ins>

* 1-> Select Roles and click on create Role

![alt text](17.png)

* 2->Select the type of entity depending on the type of access you want to give to the resource
* 3-> select a service from the drop down

![alt text](18.png)

* 4-> Select a service from the list

![alt text](19.png)

* 5-> Select a use case for that service

![alt text](20.png)

* 6-> Select the type of access

![alt text](21.png)

* 7-> Create a name for the role

![alt text](22.png)

* 8-> Select create role

![alt text](23.png)

* ##### <ins>Creating a custom IAM policy<ins>

* 1->Select policies
* 2-> select Create policy

![alt text](24.png)

* 3-> Select the type of service as per the requirements

![alt text](25.png)

* 4-> Allow the access level as per the requirements

![alt text](27.png)

* 5->Slect the types of actions that needs to be run as per the policy

![alt text](27-1.png)

* 6-> Review the permissions and select create policy

![alt text](28.png)

* 7->Create a name for the policy

![alt text](29.png)

* 8->Select create policy

![alt text](30.png)

* 9->Now You can see a custom policy has been created based on the access given to the policy

![alt text](31.png)
