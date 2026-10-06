# Git Collaboration Practice

## Pair Information
- Student A: Renzo Widjaja
- GitHub username: Renzowidjaja
- Student B: Max Endler
- GitHub username: MaxEndler7

## Branch Work
- Feature branch created: Yes
- What changed on the branch: Pink branch merged from local machine to main/origin connected to Git. 
- Who merged it into `main`: Student B, Max Endler

## Conflict Reflection
1. Why did the intentional conflict happen?
The conflict happened because Student A and Student B both changed the same line within the index.html file, but in different ways. Student A pushed their change to the remote repository, while Student B made a different change to the same heading without first pulling Student A's newest version. When Student B later tried to sync to the repository, Git found two different versions of the same line and thus it created a merge conflict. 

2. How did you resolve it?
We resolved the conflict using VSCode's conflict-resolutions tools. Student B pulled the latest remote changes and VSCode showed the conflicting resolutions using the resolve merging feature. We reviewed both the changes and replaced them with the required final heading, Final team decision: Evaluate Saas and hybrid options. After confirming that no conflict markers were left, Student B staged the file and committed the resolution, and lastly pushed/synced to GitHub. 

3. Give two practices that can reduce unnecessary Git conflicts on a real team.
   - Team members should always pull or sync the latest version of the repository before they begin editing so they are working with the most recent updated changes. 
   - Team members should communicate about which files or sections they are currently working on so that multiple people do not make conflicting changes to the same lines at the same time. 