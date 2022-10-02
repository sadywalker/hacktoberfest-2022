<a><img src="HACKTOBER.png" width="1000px"></a>


This project aims to simplify and guide the way for beginners to make their first contribution to open source . 
If you are looking to make your first contribution. This repository is the right place to start.

## Prerequisites:
* Install git in your machine.
* Have basic command line experience.

## Follow the given steps:

1. Fork this repository 
   Click the button on top right corner labelled fork.

2. Clone this repository using the link into your local machine.
   On the forked repo click the green button labelled code and copy the https url.
   Once it is copied open the terminal/cmd and type in the following code
   ```
    git clone "http url you just copied"
    ```
    
3. Going to the required project directory

   ```
    cd HacktoberFest-Projects-2021
    ```

4. Create a branch
   The best practise is to create another branch work on it and finally merge it .
   So after changing to project directory ,to create a new branch type in the following code.
   ```
    git checkout -b your_new_branch_name
    ```
    for example : 
    ```
    git checkout -b branch-2
    ``` 

5. Add the necessary contribution and commit those contributions.
    After making the changes type in the below command. This command will let you know which files have been modified.
   ```
    git status 
    ```
    Add the changes to the branch you just created using the below command.
     ```
    git add .
    ``` 
    Now commit those changes using the below command:
    
     ```
    git commmit -m "The changes that you done must be mentioned here"
    ```
<!--  
6. Merge the branch into the main branch -->

6. Push changes to github
   Push your changes using the below command:

    ```
    git push origin branch_name
    ```
    replace branch_name with the name of the branch you created earlier.
    
    For example:
    
    ```
    git push origin branch-2
    ```
7. Submit your changes for review
    If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
    Then if you want to mention anything about the changes you made type it in and finally submit the pull request.

## Rules and Regulations

1. Pull requests can be submitted to any opted-in repository on GitHub or GitLab

2. The pull request must contain commits you made yourself.

3. If a maintainer reports your pull request as spam, it will not be counted toward your participation in Hacktoberfest.

4. If a maintainer reports behavior that’s not in line with the project’s code of conduct, you will be ineligible to participate.


### Examples of Low Quailty Contributions

+ Pull requests that are automated e.g. scripted opening pull requests to remove whitespace / fix typos / optimize images.

+ Pull requests that are disruptive e.g. taking someone else's branch/commits and making a pull request.

+ Pull requests that are regarded by a project maintainer as a hindrance vs. helping.

+ Something that's clearly an attempt to simply +1 your pull request count for October.

+ Last but not least, one pull request to fix a typo is fine, but 5 pull requests to remove a stray whitespace is not.
