# Git Assignment - Logicult





    a. What is an issue?

    Ans.An issue in Github is a feature to keep track of tasks and discussions within any project. They are created in a repository to plan, discuss and track progress of any task undertaken with respect to the project. 
	They are suitable for a variety of scenarios (It could be a bug that needs fixing or a new feature idea). Issues are created with a Title and Description and can be assigned to specific team member(s), project and 
	tied to a milestone achievement. Overall it is a great collaborative tool.

    b. What is a pull request?

    Ans.A pull request is a tool to propose changes or additions/work done to the repository of a project hosted on GitHub. It enables project team members to notify others about their work done and to request feedback or review 
        of those changes before merging them into the main branch. Other people can review your work, give feedback, and together the team decides if it should be added to the main branch of the repository.

    c. How do I open up a pull request?

    Ans.We open a new branch on Github repository. We do our assigned work in this new branch. Now to seek feedback and reviews from other team members we stage, commit and push the code to the new branch. Then we log into Github 
        repository and click on PULL REQUESTS tab. Make sure we change to new branch and compare it to main branch. On the "Compare changes" page, select the branch you pushed your changes to from the "compare" dropdown menu. 
        We should always give a title and description for your pull request, describing the changes we have made and any other relevant details. Finally, we click the “Create Pull Request” button to submit to our team.

    d. Give me a step by step guide on how to add someone to your repository.

    Ans.1.We go to our repository on GitHub.
	2.We have to press the “Invite a Collaborator” button in our settings tab.
	3.We will be give a choice to find the collaborator using their username, email ID or full name.
	4.Click on the "Add" button. We can also choose a permission level as to what the collaborator can do.

    e. What is the difference between git and GitHub?

    Ans.Git is the local version control software for managing my work done on my workstation while GitHub is an online platform that enhances collaboration and visibility by hosting the whole project specific Git repositories and 
	providing many features to enable multiple team members in multiple locations to work on same project related tasks. 

	Changes made with Git are visible only on my workstation unless I explicitly push them to a remote repository online. GitHub provides accessibility to our project's codebase to anyone authorized as part of project team 
	(even client team). It serves as a platform for showcasing our (individual and company’s) work, sharing it with others, and receiving feedback or contributions from all team members. Github has many features like pull 
	requests, issue tracking, project boards etc enabling us to work together as a team.

    f. What does git diff do?

    Ans.This command compares different versions of the same project (code) and shows the changes made to the files of the project. For example, if I have made some changes to a file but haven't committed them yet, git diff will 
	show exactly what I have changed since my last commit. It's a good way to keep track of progress made and make sure everything is in order by letting me double-check my work before moving forward.

    g. What is the main branch?

    Ans.The main branch is like the most correct up-to-date master copy of your project on which the whole project team is aligned as on date (evolving project objectives may change the scope and deliverables). When we start a 
	new project, we usually begin working on the main branch. We do the work in our branch and align team members by seeking feedback through pull requests. Once the code or task is aligned between team members, it will get posted 
	in main branch.

    h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

    Ans.To make sure the changes and work we have done is reviewed by a larger group who combined will have the whole knowledge of the project, we should never push our changes to the main branch. If the proposed changes are not Ok 
	from any angle, the whole code master file may suffer and it may take a lot of time, effort and resources to reverse the changes. Hence it is always advisable to create a new branch and push our changes to that branch only. 
	Once it is approved (via process of Pull Requests) and compared it can very easily be merged into the main branch.
