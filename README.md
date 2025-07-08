### ♨♨ There are 3 tasks specially:

  **Task 1:** ANSIBLE PROVISIONING (Using the control node install amazon.aws collection and using boto3-python module From 3 instances)
  
  **Task 2:** PASSWORDLESS AUTHENTICATION (using .pem file or passsword establish a passwordless authentication)
  
  **Task 3:** Configuration Management (Make a Playbook or Role to Shutdown the systems which are ubuntu)
  

### 👻👻 Things To Know:
  
**Ansible idompotency nature** : You'll get to know that when you form 2 instances of same type it'll say the same task is repeated and i'm going to skip this..
 for that purpose you've to diffrentiate that task with proper naming or tags

**Ansible Conditioning** : As compared to other programming languages ansible runs on yaml and in that file you've to condition that using **when:** keyword.

#### ✔✔ Below image you can see the output of the playbook stop.yaml

# ✨ Terminal:

![ubuntus only shutdown](https://github.com/user-attachments/assets/a71d1c71-a886-4533-8a9d-7691c331553f)


#### ✔✔ The Amazon AWS screen is showing that 2 of instances are went down which belongs to debian family..


![aws folder](https://github.com/user-attachments/assets/01a710fe-a1a5-44ae-989a-b3cd1f0a912e)
