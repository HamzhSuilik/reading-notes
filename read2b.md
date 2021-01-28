# version control VCS

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time , Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

**there are three Types of version control:**

- Local Version Control Systems :


![image](https://static.packt-cdn.com/products/9781849517522/graphics/7522_01_03.jpg)


- Centralized Version Control Systems :

![image](https://lh5.googleusercontent.com/OLkIV5zi1otmabwR4v0LhvGekYUkktm5N96VgGHtv_axmUQdT0AG0JHowXQve01uf67w9Ewp7kDeH0MUw-m1fL_fPbVE20pPuTnErkEE_7kgWxTj98d6P6MoC535ntY8aw)


- Distributed Version Control Systems :


![image](https://lh6.googleusercontent.com/VlwLz0TUa8q7aKfDYkCKU-51_Y1Op9DGauhbNVKi0HNCe1XB86EXMaYtulgP0NmakqhNlpd7vreaIJXAuIcQ0inENGESmTTfEErl8pe_GVhcBx0pOFHobLN1kWrAhWU2fA)


## Git

![image](https://notme20n.files.wordpress.com/2020/01/git.jpeg)

**Git**  is a distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development ,  Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.

Git is software that runs locally. Your files and their history are stored on your computer. You can also use online hosts (such as GitHub or Bitbucket) to store a copy of the files and their revision history.

**Git Repositories**
A Git repository (or repo for short) contains all of the project files and the entire revision history. You’ll take an ordinary folder of files (such as a website’s root folder), and tell Git to make it a repository. This creates a .git subfolder, which contains all of the Git metadata for tracking changes.

**Remote Repositories (on GitHub & Bitbucket)**
Storing a copy of your Git repo with an online host (such as GitHub or Bitbucket) gives you a centrally located place where you can upload your changes and download changes from others, letting you collaborate more easily with other developers.

**Commits :**
A commit logs a change or series of changes that you have made to a file in the repository. A commit has a unique SHA1 hash which is used to keep track of files changed in the past. A series of commits comprises the Git history.

**Branches :**
A branch is essentially a unique set of code changes with a unique name. Each repository can have one or more branches. The main branch — the branch where all the changes eventually get merged into - is called the master.