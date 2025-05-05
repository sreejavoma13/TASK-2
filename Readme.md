![conflict](<Screenshot (5).png>)
![Resolved Conflict](<Screenshot (6).png>)
<h3>Detailed Description of Resolving Merge Conflicts</h3>
Two branches 
1.feature/add-content
2.feature/update-styling

change in Branch-1 -> added border with border:solid 10px black
change in Branch-2 -> added border at the same positiomn with border:solid 10px blue
I performed a git merge feature/update-styling when I am in feature/add-content branch
Since, There is a change at same place 
conflict occurs
Resolve the conflict in merge editor
keep the current changes or incoming changes or both changes
then confirm merge
merge conflict is resolved !!

<h3> Assignment -4 </h3>
<h4>Code automation with Husky and lintstaged</h4>
<p> These are the tools which automate codequality checks and keep you codebase clean and consistent.</p>
<p>Husky automates critical code quality checks right before commiting,catching errors and maintaing consistentcoding styles without need for manual intervention.It is like a security Guard for code base 

to install --> npm install husky --save-dev  
initialize the husky precommit script--> npxhusky-init
it will create .husky/pre-commit file</p>

<p>lint staged performs code quality checks and formatting only on those files which are about to be commited i.e only on staged files
to install -> npm install lint-staged --save-dev</p>
