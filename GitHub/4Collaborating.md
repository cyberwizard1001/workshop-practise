Hey there! We're slowly moving up the ranks now, having learnt basic operations of Git. At this point, if all we wanted to do was to create and manage our own repositories, we're pretty much good to go! However, one of the key benefits of using GitHub as our VCS is the powerful collaboration features it enables. To begin with, let's learn and practise a few such commands, shall we?

### Fork:

Forking is an important feature. It is used to create an exact copy of the repository you're trying to 'fork' in your account. Say, I find a repository that I really like and want to make a few changes to. How do I do that?

-   To fork a repository, open the repository page on GitHub.
-   Once there, look for the fork button in the top right of the page, and click on it.
-   Tadaa! Your own copy of the repository is ready for you to work on :)

<br>

-   We will begin by forking this repository.
-   Open the repository page: (https://github.com/cyberwizard1001/workshop-practise)
-   Click on the fork button.
-   Watch as a copy of this repository is created in your account!
-   You will be able to access this at `github.com/YourUsernameHere/workshop-practise`
    where `YourUsernameHere` is your username.

### Clone:

Now, we have a copy of the repository we were interested in, and the next step is to work on it and apply the changes we wish to see. Of course, we could use the text editor on GitHub to make these changes but you might say _'Hey, I like working in my IDE!'_ and they have the solution ready!

To obtain a local copy of this repository, we will be cloning it. Cloning is the act of creating a local copy of a repository that lives in GitHub. From that point on, we'd be able to push, pull, commit and do much more. To clone a repository, we need it's URL. At this point of time, to make things easier, we'll be cloning repositories that are under our _username_.

-   Open `github.com/YourUsernameHere/workshop-practise` in your browser (where `YourUsernameHere` is your username)
-   Locate the green colored **_Code_** button and click on it, then copy the URL (there's a `copy to clipboard` button there as well).

-   Search for Git CLI in the Start menu on your local machine and click on the Git CLI app. A terminal window should open at this point, pointing to your home directory.
-   Navigate to the directory you want this repo in (using the _cd_ command) and run the following command:

    `git clone https://github.com/YourUsernameHere/workshop-practise.git `

(Paste the downloaded link by right clicking and selecting _paste_ or using the Shift+Ins keyboard shortcut or any other pasting shortcut that applies to your system)

Now, press **ENTER**.

And we're done! You should see the files downloading at this point. Once the command is complete, you have an up to date copy of the code that's on your repository on your local machine!

### branch

### checkout

### add

`git add . ` ===> your gateway to the staging area

### merge

### cheesy outro

#### note: fetch, it's difference from pull
