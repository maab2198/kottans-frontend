### Lesson 1

1. How did viewing a diff between two versions of a file help you see the bug that
was introduced?

    - The diff command helped us to see the difference between two versions and we saw that "space" changed unpredictably.

2. How could having easy access to the entire history of a file make you a more
efficient programmer in the long term?

    - It's useful for bug-fixing and experiments because we are able to come back to the checked and reliable position

3. What do you think are the pros and cons of manually choosing when to create a
commit, like you do in Git, vs having versions automatically saved, like Google
docs does?

    Google 
    - New information is allways saved 
    - Saving with regular intervals
    - Useful for fast-writing documents or like a store for files 

    Git
    - You can control what and when to save 
    - Every commit make sense (or not))) and pretty name
    - It easy to work with commit history
    - Usefull for long and changeable projects (writing a novel)

4. Why do you think some version control systems, like Git, allow saving multiple
files in one commit, while others, like Google Docs, treat each file separately?

    - Google Docs work with one single document, git is for projects, if some file changes it meters for the whole project 

5. How can you use the commands git log and git diff to view the history of files?

    - git log - show commits history 
    - git diff - changes between 2 commits

6. How might using version control make you more confident to make changes that
could break something?

    - Possibility to come to the fixed point if something goes wrong

7. Now that you have your workspace set up, what do you want to try using Git for?

    - For  kottans :smiley_cat:

### Lesson 3
1. What happens when you initialize a repository? Why do you need to do it?
    -   Creates "invisible" .git folder. we use it to create repository, which is empty at the moment
2. How is the staging area different from the working directory and the repository? What value do you think it offers?
    - The staging area allows you to group some files, out of all of the changed files in the working directory, so that the grouped files can be committed together.
    - add file => git add file
    - show list of selected files => git status
    - Working directory is just a folder in the computer. Git repository knows commit history and usually connects remote repositories (at Github for example)

3. How can you use the staging area to make sure you have one commit per logical
change?
    -  It's usefull to group files related to each logical change, adding them to the staging area, and then ommitting them. Thus we creates commits with logical connected changes.

4. What are some situations when branches would be helpful in keeping your history
organized? How would branches help?
    -   You can use git flow paradigm: there're some types of branch and every type has it own significance.We have branhes for bugfixisng, working process, features and preparetion to relese 

5. How do the diagrams help you visualize the branch structure?
    -   We can see whole commit tree and visualize all branches history and connections

6. What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?
    -   The result of merging two branches together is a combined commit with all the changes from both branches. 

7. What are the pros and cons of Git's automatic merging vs. always doing merges
manually?
    - More often git can solve the conflict automatily but whe people make some shit it asks for help

### Lesson4

1. When would you want to use a remote repository rather than keeping all your work
local?

    - For collaboration with other people. To use the repoistory from other computer and have a backup.

2. Why might you want to always pull changes manually rather than having Git
automatically stay up-to-date with your remote repository?

    - That might cause some confusion when you are working with team of developers.

3. Describe the differences between forks, clones, and branches.  When would you
use one instead of another?

    - fork - you have connection with parent repository. used only for remote repositories.
    - clon - creates copy from any git repository.
    - branches - created inside of one single git repository and all the user of the repository can know what branches are there.

4. What is the benefit of having a copy of the last known state of the remote
stored locally?

    -  You can see that state of the remote even if you're offline. It also allows you to do comparisons with what is on the remote.

5. How would you collaborate without using Git or GitHub?  What would be easier,
and what would be harder?

    - Google Disk, Telegram and  Dropbox. There're good foork books or documents (I'm not goimg to them).Github is usefull for code and "alive" documentation or even for blogs

6. When would you want to make changes in a separate branch rather than directly in
master?  What benefits does each approach have?

    - Working in a separate branch ensures that your master branch is
    always kept in a working state. You can try and experiment new
    functionality in the new branch untill you are sure
    it works without breaking anything.