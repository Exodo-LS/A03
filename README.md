# A03
***
### Part 1 Installation of Github, Webstorm, and Git:
I began my process with initially making a GitHub account. Head to https://github.com/ and click sign up. You will be asked to create a username and password. You will also need to provide a valid email address. After that, you will need to verify your account by answering a puzzle that is provided. Once completed, you have created your GitHub account. Double-check your email to make sure you do not need to verify any extra information.

To download GIT, I went to https://git-scm.com/downloads and downloaded the .exe file. I opened the .exe file and went through the installation process. Use the recommended options it gives you to make it a smoother experience. There will be a terminal that pops up, and you are able to use GIT. I ran these two commands to sync up to my GitHub: 
* git config --global user.name "Name" (Replace "Name" with your name and keep the double quotation marks)
* git config --global user.email "email@example.com" (Replace the email with your email and keep the double quotation marks)

Now it is time to install and configure Webstorm. I went to www.jetbrains.com/webstorm/download/#section=windows to download the Webstorm software. Once downloaded, I ran through its installation process. I recommend using the recommended settings if you are still new. Once completed, head to settings and version control. Click on Git and choose the path to the GIT executable. Change the shelve option to stash and click test. You will know if it works by it telling you the version under the path.

To validate if you successfully linked everything, create a new project and new file. Insert any information into that file. Click VCS -> Import into Version Control -> Create Git Repository and click OK. You commit the changes by VCS->Git -> Commit File and click commit. You may need to input your username and email if it is the first commit. Afterwards, Click VCS -> Import into Version Control -> Share Project on Github and click share. Head back to GitHub and check if the file is in the repository. Just like that, you now have all three softwares linked.

***
### Part 2 Defining Words:

* **Branch** - A branch is a parallel version of a repository, but does not affect the primary or main branch
* **Clone** - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy.
* **Commit** - It is an individual change to a file or set of files (also known as a revision).
* **Fetch** - Adds changes from the remote repository to your local working branch without committing them.
* **GIT** - It is an open source program for tracking changes in text files.
* **Github** - It is where over 65 million developers shape the future of software, together. (Yes that is the website bio)
* **Merge** - Takes the changes from one branch and applies them into another. (Branches must be in the same repository)
* **Merge Conflict** - A difference that occurs between merged branches. Can happen when people make different changes to the same line of the file or when one person makes changes while another deletes the same file. Must be resolved before merging.
* **Push** - To send your committed changes to a remote repository.
* **Pull** - The act of fetching changes and merging them.
* **Remote** - This is the version of a repository or branch that is hosted on a server.
* **Repository** - The folder where your projects are stored.
```
The reference I used for this was the glossary on GitHub: https://docs.github.com/en/github/getting-started-with-github/quickstart/github-glossary#repository
```