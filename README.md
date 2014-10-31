# Lab 8: Starting your Group Project

#### Step 1: Making friends :D
- Get into your project groups

#### Step 2: First Pull Request
- Create a repo on github on one of the user's accounts, with an initial README
- Name it anything you wish :)
- Have everyone clone the repo
- Have one person pullrequest the following into the README.MD
- Have another person comment "Looks great!" and merge it in

```
# Our Project is Awesome
By: Person1, Person2, Person3, Person 4
```

#### Step 3: Conflicts
- Designate each team member to be Person1, Person2, etc.
- Have everyone submit a pull request, without merging, with their name replacing Person1, Person2, etc.
- As soon as there are 4 PRs (or less if you have less members) merge in the changes one by one.
- Fix conflicts as they come up!
- To fix a unmergeable branch:
    - On the branch (locally) do ```git pull origin master```
    - ```git status``` to figure out which files need to be fixed
    - open the file, delete the <<<< >>>>> lines, save the final version you want it to be
    - ``` git add <filename>``` OR ``` git add . ``` to tell git you want to commit it
    - ``` git commit -m "Fix merge conflict```
    - ``` git push -u origin HEAD ```
    - Go on github, and try to merge it now!
- If you're running out of time, just do one merge conflict example:
    - i.e have person1 fill out person1, and have person2 fill out person2,person3,person4

#### Final Submit
- Fill out the [Google Form](http://goo.gl/eI6VqB) with your project team

## Quick Git Commands:
```
git add -A 
git commit -m "commit message"
git branch branch-name
git checkout branch-name
git pull origin master
git push -u origin HEAD
git status
git log

If you need to know what these commands do, google search them! And if still confusing, 
ask one of the TAs for help :D
```
