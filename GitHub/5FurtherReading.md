We have created a repository, downloaded a local copy, edited that, and uploaded that to remote and also updated the local repository with contents from the cloud. Now that we are comfortable with all these basics, this is where the real usefulness of GitHub starts to exhibit itself. 


## Branching 

Assume you are editing a piece of code that is already working and is being used by other people. You have now decided to add a new feature but you're not sure if it's going to branch. Sure you can fork the repository to another account and try out the changes there but really? A new account just to test out a new feature? Ugh.

This is where branching comes in. By default, all code is saved to the default branch, **main**. If we want to make any changes but not affect existing code, we do this by creating a new branch. A new branch essentially means that the existing code will remain unchanged and changes are committed to a new copy of the code. 

You can now safely add your new feature to your project while also ensuring that existing code continues to work. Once done, you can then **merge** your changes with the *main* branch. 

You can create a new branch by running the following command: 

```git branch branch-name ```


This creates a branch with the branch name '**branch-name**'.

Now that a branch has been created, we have to switch over from committing to the *main* branch to the branch that we just created. This can be done by running 

```git checkout branch-name```

To shorten time, we can combine these two commands to create a new branch and checkout to the same in a single line:

```git checkout -b branch-name```

Now, you can modify your code and all modifications will be reflected in the branch *branch-name*. 

**NOTE:** Before you go back to your master/main branch, be sure to commit all changes or else GitHub will not let you switch back to master/main. 

Once you're done adding your feature and you know it works, there's no job for the branch anymore! This means we can move over this code to main and delete this branch. 

To do so, run the following code: 

``` git merge branch-name```

This will merge the branch with main, and will remove the branch. 

