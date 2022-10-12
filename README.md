# ANSIBLE REFACTORING AND STATIC ASSIGNMENTS (IMPORTS AND ROLES)

Project 12 builds on what we learnt in project 11.  Here we learn about Ansibles feature to help better organise our playbook and make them reuseable.


### ROLES

Roles is a feature of Ansible that makes our playbook reuseable. If you are a developer see them as packages you import into your code. Just like in programming you can author your roles and store them in a public repository known as *GALAXY*.
 
You can also make use of publicly available roles in galaxy as well


To download a publicly available role run the command below:


 `ansible-galaxy <name of the role>`
 
 
### IMPORTS

Imports helps you add playbooks into master playbook file. This feature helps in organisation of your. You get to keep related playbooks in one file and import it into a master playbook when needed.


These are the screenshots of the project.


![Screenshot from 2022-10-11 19-10-28](https://user-images.githubusercontent.com/23356682/195304268-eb9a0c15-6925-40f5-841a-5e25ee1887fa.png)
![Screenshot from 2022-10-11 19-36-09](https://user-images.githubusercontent.com/23356682/195304272-77c95064-d63e-417a-847d-13922b9f851f.png)
![Screenshot from 2022-10-11 19-40-41](https://user-images.githubusercontent.com/23356682/195304277-d5d91ac2-0647-4ea1-a2f1-71590d3941ea.png)
![Screenshot from 2022-10-11 19-42-55](https://user-images.githubusercontent.com/23356682/195304284-4165db88-7106-4662-8b70-3999cc6d1741.png)
![Screenshot from 2022-10-11 21-02-34](https://user-images.githubusercontent.com/23356682/195304298-bbcfe2ec-2671-4a10-b45b-6a184b260385.png)
![Screenshot from 2022-10-11 21-03-32](https://user-images.githubusercontent.com/23356682/195304304-91d223c4-4159-4818-aeee-d8e0dd2f3683.png)
![Screenshot from 2022-10-11 21-03-44](https://user-images.githubusercontent.com/23356682/195304311-be4f5460-ad71-4f15-8f93-1ed8b7ce2e10.png)
![Screenshot from 2022-10-11 21-11-37](https://user-images.githubusercontent.com/23356682/195304314-bf043795-c5f1-4fe6-aa1f-62e6a10be2fb.png)


