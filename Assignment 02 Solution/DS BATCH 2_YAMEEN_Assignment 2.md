<!-- Style to make pdf dark -->
<style>
@page {
    margin: 0cm;
    @bottom-right {
        content: counter(page) " of " counter(pages);
        margin: 20px;
    }
    
}
html {
    background-color: #1e1e1e; /* This sets the background color for the entire page */
}
body {
    background-color: #1e1e1e; /* Choose your desired background color */
    color: #d4d4d4;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    margin: 30px 30px;  
    break-inside: avoid;
}

a {
    color: #007BFF; /* Change this to the color you want */
}

h1, h2, h3, h4, h5, h6 {
    color: #61dafb;
}

pre {
    background-color: #2d2d2d;
    color: #d4d4d4;
    padding: 10px;
    border-radius: 5px;
    overflow: auto;
}

ul {
    list-style-type: square; /* Change this to the shape you want */
}
</style>

<!-- Style End -->

# <center> Assignment 2 </center>  
 
#### This assignment aims to familiarize with Git and GitHub by creating a project with multiple branches, incorporating the merge concept, generating a README file, and utilizing the .gitignore file for project management.

---

<!-- Navigation with Internal Links -->

## Navigate from here
- [Step 1 - Account in GitHub](#step-1---account-in-github)
- [Step 2 - Creating a new Repository on Github](#step-2---creating-a-new-repository-on-github)
- [Step 3 - Clone the Repository to local machine](#step-3---clone-the-repository-to-local-machine)
- [Step 4 - Create Multiple Branches](#step-4---create-multiple-branches)
- [Step 5 - Commit Changes](#step-5---commit-changes)
- [Step 6 - Merge Branches](#step-6---merge-branches)
- [Step 7 - Generate a README file](#step-7---generate-a-readme-file)
- [Step 8 - Add .gitignore file](#step-8---add-gitignore-file)  
- [Step 9 - Push Changes to GitHub](#step-9---push-changes-to-github)


<!-- Step 1 -->

# Step 1 - Account in GitHub
![Alt text](screenshots/1_github_profile.png)
### <center>[Go To Github Repository](https://github.com/YameenAli/Online_Exams-Cheating-Detection)</center>


<!-- Step 2 -->

# Step 2 - Creating a new Repository on Github

1- Create a new repository on GitHub with a name Online Cheating Detection.  
2- Initialize repository with README.md

![Alt text](screenshots/2_create_repository_full.png)

 After Create Repository, You can see the following Screen

![Alt text](screenshots/3_after_create_repository.png)


<!-- Step 3 -->

# Step 3 - Clone the Repository to local machine 

Clone the content from remote repositoy to local repository  

1- Create new Folder Assignment_2_Git
![Alt text](screenshots/4_empty_folder.png)

2- Copy the url from here
![Alt Text](screenshots/5_git_clone_url.png)

3- To run Git Clone Command in Terminal first we have to run Git init in a folder where we want to initialize and than clone remote repository.

    Git Init
![Alt text](screenshots/6_git_init.png)
   
    Git Clone (paste copied url of remote repository)
![Alt text](screenshots/7_git_clone.png)


<!-- Step 4 -->

# Step 4 - Create Multiple Branches
Initially we have <code>main</code> branch now we have to make more branches  



    git branch (branch_name)

I created three branches for my project that are listed below by using above command
> Data Collection and Preprocessing Branch 
>> Model Development Branch
>>> Integration and Deployment Branch

![Alt text](screenshots/8_branches.png)


<!-- Step 5 -->

# Step 5 - Commit Changes

### Initial Commit <code>origin/Main</code>
![Alt text](screenshots/9_initial_commit.png)

### Commit in <code>Main</code> Branch
    
    git commit -m "Initialize the project structure and add the main script (main.py)"

![Alt text](screenshots/9.1_commit_in_main_branch.png)

---
### Commit in <code>Data_Collection_and_Preprocessing</code> Branch

First we have to checkout from main branch to Data_Collection_and_Preprocessing branch

    git checkout Data_Collection_and_Preprocessing

Now we have to commit our changes in this branch

<code>Before committing changes in Git, you need to stage the changes. Staging is the process of preparing and selecting the changes you want to include in the next commit</code>

To add all changes

    git add .

### First Commit

    25e91d34812f019fa9d118a39d867b0af5813760 
![Alt text](screenshots/10_Gathered_initial_Dataset_PY.png)

![Alt text](<screenshots/10.1_Gathered Intitial Dataset.png>)

### Second Commit

    2b4610414d2ba7d4925e458d3ca989326fa7cce0
![Alt text](<screenshots/10.2_Data cleaning and preprocessing.png>)

![Alt text](<screenshots/10.3_Data cleaning and preprocessing.png>)

---

### Commit in <code>Model_Development</code> Branch

First we have to checkout from Data_Collection_Preprocessing branch to Model_Development branch

Now we have to commit our changes in this branch
### First Commit

    e020febad8973247f38050264878624b0de877f8
![Alt text](screenshots/11_Model_Development.png)
![Alt text](screenshots/11.1_First_commit.png)

### Second Commit

    58afaa8ada4d19bab67657322aa76355cafa3697
![Alt text](screenshots/11.3_python_Second_Commit.png)

![Alt text](screenshots/11.2_Second_Commit.png)

---
### Commit in <code>Integration_and_Deployment</code> Branch

First we have to checkout from Model_Development branch to Integration_and_Deployment branch

Now we have to commit our changes in this branch
### First Commit

    f6f702f116367b9e85514a66c25dac10e603a3de
![Alt text](screenshots/12_Py_Integration_and_Deployment.png)

![!\[Alt text\](image.png)](screenshots/12.1.png)

### Second Commit

    fa262f3bd6fe03cff3b6edc845296c2d37f4e881

![Alt text](screenshots/12.2.png)



# Step 6 - Merge Branches

### Start with the <code>Main</code> Branch

Ensure you are on the Main branch:

    git checkout main
![Alt text](screenshots/13_Checkout_main.png)

### Merge <code> Data_Collection_Preprocessing</code> Branch

    git merge Data_Collection_Preprocessing

### Merge <code>Model_Development</code> Branch

    git merge Model_Development

### Merge <code> Integration_and_Deployment</code> Branch

    git merge Integration_and_Deployment
    
![Alt text](screenshots/13_merged_branches.png)



# Step 7 - Generate a README file

### In the <code>Main</code> Branch
![Alt text](screenshots/14_README_file.png)

commit into main
![Alt text](screenshots/14.1_readme_commit_into_main.png)



# Step 8 - Add .gitignore file

![Alt text](screenshots/15_gitignore.png)

<br>
<br>
<br>


# Step 9 - Push Changes to GitHub
    git push origin main
![Alt text](screenshots/16_push_origin.png)

![Alt text](<screenshots/16.1_push to remote.png>)