#demo-repo  
#Git and GitHub for Beginners - Crash Course
https://www.youtube.com/watch?v=RGOj5yH7evk&t=101s

Learn about Git and GitHub in this tutorial. These are important tools for all developers to understand. Git and GitHub make it easier to manage different software versions and make it easier for multiple people to work on the same software project.

>git clone https://github.com/mlonggit/demo-repo.git

afterr making chges 
>git status

>git add . 
or git add index.html 
.all files
U = untrack
add to staging  now commit

>git commit -m "add index.html" -m "some description"
now only save locally not on git hub yet
use git push
>git push
----------------------------------
PS C:\eProjects_2021\GitHubRepo\demo-repo> git add .
PS C:\eProjects_2021\GitHubRepo\demo-repo> git status
On branch main
Your branch is up to date with 'origin/main'.      

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   index.html
        modified:   readme.md

PS C:\eProjects_2021\GitHubRepo\demo-repo> git commit -m "add index.html" -m "some description"
[main 7e70335] add index.html
 3 files changed, 12 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 index.html
PS C:\eProjects_2021\GitHubRepo\demo-repo> 
-------------------------
PS C:\eProjects_2021\GitHubRepo\demo-repo> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 503 bytes | 503.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mlonggit/demo-repo.git
   af1f005..7e70335  main -> main
PS C:\eProjects_2021\GitHubRepo\demo-repo> 
------------------------------
