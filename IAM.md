# <ins>Creating IAM user using AWS management console<ins>

* ##### This tutorial demonstrates creating a new IAM user with adminstrator access using AWS management console

* ##### You need to login as a root user to the management console to create an IAM user

#### <ins>Create user<ins>

* 1-> Select the IAM 

![alt text](images/1.png)

* 2-> Click on users

![alt text](images/2.png)

* 3-> Click on Create User

![alt text](images/3.png)

* 4->Give an user name

![alt text](images/4.png)

* 5->Select Attach policies directly

![alt text](images/6.png)

* 6->Select Adminstrator access

* 7->Select Create User

![alt text](images/7.png)

* ##### Now you can see a user has been created with the name test-user

# <ins>Create user group<ins>

* ##### This tutorial demonstrates creating user group using AWS management console

* 1-> Select the users

![alt text](images/9.png)

* 2-> Select Create group

![alt text](images/10.png)

* 3-> Create a group name

![alt text](images/11.png)

* 4-> Select the type of access

![alt text](images/12.png)

* ##### Now you can see a user has been created with the name test-grp

![alt text](images/13.png)

* # <ins>Adding an user to user group that we created or existing user groups<ins>

* 1-> Select the group name


![alt text](images/13-1.png)

* 2-> Select Add users

![alt text](images/14.png)

* 3-> Select the users you want to Add

![alt text](images/15.png)

* 4-> Add Users

![alt text](images/16.png)

* # <ins>Creating a IAM  Role using console<ins>

* 1-> Select Roles and click on create Role

![alt text](images/17.png)

* 2->Select the type of entity depending on the type of access you want to give to the resource
* 3-> select a service from the drop down

![alt text](images/18.png)

* 4-> Select a service from the list

![alt text](images/19.png)

* 5-> Select a use case for that service

![alt text](images/20.png)

* 6-> Select the type of access

![alt text](images/21.png)

* 7-> Create a name for the role

![alt text](images/22.png)

* 8-> Select create role

![alt text](images/23.png)

* # <ins>Creating a custom IAM policy<ins>

* 1->Select policies
* 2-> select Create policy

![alt text](images/4.png)

* 3-> Select the type of service as per the requirements

![alt text](images/25.png)

* 4-> Allow the access level as per the requirements

![alt text](images/27.png)

* 5->Slect the types of actions that needs to be run as per the policy

![alt text](images/27-1.png)

* 6-> Review the permissions and select create policy

![alt text](images/28.png)

* 7->Create a name for the policy

![alt text](images/29.png)

* 8->Select create policy

![alt text](images/30.png)

* 9->Now You can see a custom policy has been created based on the access given to the policy

![alt text](images/31.png)

* # <ins>Creating and logging with IAM user to Management console<ins>

* 1->Create user

![alt text](images/32.png)

* 2->Create a name for the user
* 3->select provide access to management console
* 4->select create an IAM user


![alt text](images/33.png)

* 5->Select Auto-generated password(You can also create a custom password) and proceed to next step

![alt text](images/34.png)

* 6->Select add user to group
* 7->Add the user to user-group which has been already with the admistrator access or you can attach adminstrator access directly

![alt text](images/35.png)

* 8-> Review the details and create the user

![alt text](images/36.png)

9-> MAke sure to copy the password on the password screen it disappers once you go back to the users screen or alternatively you can download the csv file
* 10->Download the csv file

![alt text](images/37.png)

* 11->open the downloaded csv file from the downloads folder

![alt text](images/38.png)

* 12->Copy the username and password

![alt text](images/39.png)

* Go to the login page og management console
* 13->Select the IAM user
* Give the username from the downloaded csv file and proceed to next step
![alt text](images/40.png)

* 13->Give the usename and password from the downloaded csv file

![alt text](images/41.png)

* 14->Now you logged in as an IAM user to the management console with the adminstrator access

![alt text](images/42.png)




