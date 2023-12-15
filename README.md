
Q1 - What does clone set the variable origin to represent?
    When clone is used, it sets the origin to represent the branch cloned is called
    on, including the whole history. 
Q2 - What does the command git push --set-upstream origin master do? What does remote tracking mean in this context?
    It sets the current local branch to the remote branch. Remote tracking is tracking the changes between the local copy and the remote branch.
Q3 - git pull origin master pulls the branch from the remote main and merges it to the local branch. It also takes all changes and merges them into one branch locally.
Q4 - Since it was a merge, git pull origin master didn't overwrite my local changes or any of the remote changes in any of the branches
Q5 - git pull origin master was a merge.
Q6 - The local master branch is still behind the remote master.
Q7 - No it did not delete the local copy of my branch


Here's the git log:
*   commit 28314a3c218537f4a1daf5f2eb47da40cba6bf64 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: f34860e c090ee0
| | Author: JPynx <95723218+JPynx@users.noreply.github.com>
| | Date:   Fri Dec 15 11:02:30 2023 -0700
| | 
| |     Merge pull request #2 from JPynx/Feature2
| |     
| |     This commit is being amde from the Feature2 branch
| | 
| * commit c090ee010e64299dfa604d0ed49f00e6703f58b8 (origin/Feature2, Feature2)
| | Author: JPynx <jsanchez-espino24@kentdenver.org>
| | Date:   Fri Dec 15 11:00:35 2023 -0700
| | 
| |     This commit is being amde from the Feature2 branch
| | 
* | commit f34860eef3f0f4182091a25bc6bea021af3c7a1b
|/  Author: ajabeldo24 <144931583+ajabeldo24@users.noreply.github.com>
|   Date:   Fri Dec 15 10:59:24 2023 -0700
|   
|       Update README.md
|       
|       Answered Q7
|   
*   commit 29fdfaa564cc0ddc336214a595f1181842413db4
|\  Merge: 25f8871 690e48a
| | Author: JPynx <95723218+JPynx@users.noreply.github.com>
| | Date:   Fri Dec 15 10:45:29 2023 -0700
| | 
| |     Merge pull request #1 from JPynx/AhmedBranch
:
