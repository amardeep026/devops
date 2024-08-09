# Managing Primary and secondary Repo

Ever worry about putting all your code in one basket? Recently, I faced the challenge of needing to keep my codebase safe and accessible across repos.  Managing two Git repositories—one primary, one secondary.

  The Problem:  
Relying on a single repository is risky. What if it becomes inaccessible or goes down?

  The Solution:  
Set up a secondary remote in Git. This allows you to easily push your changes to both your main repo and a backup.

 #### How to Do It:  

1.   Clone Your Primary Repository:  
      bash
   git clone <primary-repo-url>
   cd <repository-directory>
      

2.   Add a Secondary Remote:  
      bash
   git remote add secondary <secondary-repo-url>
      

3.   Push to Both Repositories:  
      bash
   git push origin <branch-name>
   git push secondary <branch-name>
      

  Benefits:  
-   Redundancy:   Your code is backed up, minimizing risks.
-   Flexibility:   Seamlessly work across multiple platforms.
-   Security:   Ensure your code is always available.

![alt text](image-2.png)