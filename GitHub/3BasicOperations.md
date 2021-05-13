# Hi there!

Now that we have successfully installed Git and configured GitHub, it's time to actually use it! 

### Setup
To create a repository and begin working on it, we first need a file location to start with! So, create a new folder in a location of your choice (say, the desktop) and give a cheeky file name.

 - **Choose your working directory**: Head to your Git window and type `pwd` to find your present working directory. You'd typically find your location to be in `/c/Users/<UserName>`. This is not really a convenient place to manage your files. So, enter your desired file location using `cd <FilePath>` (Eg: cd Desktop will take you to the path /c/Users/JohnDoe/Desktop)
 
 - **Create a folder**: We have now moved to our desired location (Psst, we can verify it using pwd). Type in `mkdir "FolderName"` to create a new folder. You'll now find that a new folder created in your file path, this will be your project location.

Note: Always make sure your current working directoy is in the location of your project.

### init

The folder we have now is an ordinary project folder. But we need to transform this folder into a **git project** to make it functional with GitHub and keep track of changes.

 - Type `git init` to initialize an empty git repository. Although there are no visible changes to your folder, this is now your brand new git repository.
 
### add 
Our git folder is empty! Let's add a file.

 - **Creating a file**: `touch <FileName>.<FileExtension>` (Eg: touch myFile.txt) will create a new file inside your folder . You will now be able to navigate in your PC to open the file, make changes and save the file.
 - **Adding to Git**: Head back to the Git Window and enter `git add <FileName>.<FileExtension>` (Eg: git add myFile.txt). The added file is now ready to be comitted (integrated into the repo).
### status 

Using the command `git status` will let us know the status of the working directory and the staging area (shows the files that are yet to be committed). It also shows us the files that are not being tracked by Git. 

### commit 

Since we have not made any commit, git status displays 'No commits yet'.

 - We can make a commit by using the command `git commit -m "<Name of your Commit>"` 
 - You can name your commit as anything that you wish, icould be a relevant title such as 'First Commit myFile.txt' or a message to be shown like "Fixed overflow bug"
 - The file that was added in the previous step is now commited.
 - To change the name of the recent commit, use `git commit --amend -m "<New name of your Commit>"`. 
 - You can also change you commit entirely by using `git add` command before you change the name.

### remote 
### pull
### push 
### log, status - with status codes 
