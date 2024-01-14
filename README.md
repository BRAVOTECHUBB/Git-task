Project done by "Okorie Fedrick Eseni"

        1. **Meaning of Versio Control**:Version control is a system that manages changes to a set of files over time. 
    It is a crucial aspect of software development, enabling multiple developers to work on a project simultaneously, tracking changes, and maintaining a historical record of the codebase. The primary goals of version control include collaboration, tracking changes, and preserving the integrity and history of a project.
         2.** Difference Between Git and Github**
            Git:

Definition: Git is a distributed version control system (DVCS) that allows developers to track changes in their source code during software development.
Functionality: Git provides the core version control functionality, managing repositories, tracking changes, and enabling collaboration among developers.
Usage: Git is primarily used for local version control. Developers can use Git to track changes in their code, create branches, commit changes, and manage the history of their project on their local machine.
                                While
GitHub:

Definition: GitHub is a web-based platform that provides hosting services for Git repositories. It extends Git by adding a web-based interface, collaboration features, and additional tools for project management.
Functionality: GitHub acts as a remote repository hosting service, allowing developers to store their Git repositories on the web. It provides a platform for collaboration, code review, issue tracking, and project management.
Usage: GitHub is used for remote hosting of Git repositories, enabling distributed collaboration among developers. Developers can push their local Git repositories to GitHub, making it easy for teams to work together, track issues, and manage projects.
        3. Other Github Alternatives: 
        a. SourceForge
        b.Bitbucket
        c.Gitlab
        
        4. Difference between Git fetch and Git Pull
    Gitfetch: git fetch retrieves changes from a remote repository but does not automatically update your working directory or merge the changes into your local branches.
Usage: Use git fetch when you want to see what changes exist in the remote repository without making any changes to your local working directory or branches.
        
           command:  git fetch origin

GitPull: git pull is a combination of two actions – git fetch followed by git merge. It fetches changes from the remote repository and automatically merges them into your currently checked-out branch.
Usage: Use git pull when you want to both retrieve changes from the remote repository and immediately update your working directory and local branch to reflect those changes.
           command:  git pull origin master
    5. Git Cherry Pick and the command: git cherry-pick is a Git command that allows you to apply a specific commit from one branch to another. It's a way of picking a commit from one branch and applying it onto another branch. This can be useful in scenarios where you want to selectively apply changes without merging entire branches.
        command: git cherry-pick <commit-hash>



    
