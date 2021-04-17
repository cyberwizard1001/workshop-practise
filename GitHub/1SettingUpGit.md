# Set up Git

### There are two ways to use git locally on your computer:

- Github CLI
- Github Desktop

### Installation and setup:

#### Github CLI:    
You can download the executable from the following page for Microsoft Windows. 

Link: https://git-scm.com/download

Once downloaded, follow the on screen prompts to install. As a beginner, it's pretty safe to not change anything and just install the default configuration. Once that is done, you will find a program called *'Git Bash'* in your Start menu. Congratulations! You've successfully installed Git. <br>

#### For other OSes: 

**macOS:** 
Assuming you have Homebrew installed and setup, you can go ahead and run: <br> <br> ``` brew install git ``` <br> <br>

**Ubuntu and derivatives:**

``` sudo apt install git ``` <br> <br>

**Fedora, RHEL based distributions:**

``` sudo dnf install git ``` <br> <br>

**SUSE based distributions:**

``` zypper install git ``` <br> <br>

**Arch based distributions:**

``` sudo pacman -S git ``` <br> <br>


#### Github Desktop:

If you want to work with Git locally and you're worried about the command line experience, you can initially download and use the GitHub Desktop interface that provides most of the essential features of GitHub. Download it and follow the onscreen prompts. <br>

*NOTE: Git has to be installed already for GitHub Dekstop to work* <br>

Download Github Desktop: https://desktop.github.com <br> 
(Download the appropriate version of Github Desktop for your operating system.)

<br> <br>

### Having an account:

At this point, you should have a GitHub account setup and functioning. If not, do head over [here][1] and sign yourself up! <br> <br>


### Configuring Git:

#### Configure Git CLI:

To begin using GitHub from your local machine, you need to set a username and email address to identify yourself while making commits and what not. To do so, we have to run a couple of commands. <br>

*Username :* ``` git config --global user.name "FIRST_NAME LAST_NAME"``` <br> <br>
*E-Mail ID:* ``` git config --global user.email "MY_NAME@example.com" ``` <br> <br> 

#### Configure Git for Github Desktop:

Github Desktop uses the email address you set in your local Git configuration to connect the commits you make with your account on Github.

#### Steps to be followed on Mac:

1. Sign in to Github.
2. On the upper-right corner of the page, click on your profile photo.
3. Select Settings from the Drop-down that appears at this point.
   <!-- photo 1. https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/configuring-git-for-github-desktop -->
4. Under Settings, click on emails. 
   <!-- photo 2 same link as in the comment above -->
5. Copy the email address you'd like to use in your local Git configuration.
6. Open GitHub Desktop and in the menu bar, using the drop down menu, click on Preferences. 
    <!-- picture 3 same comment mac setup-->
7. In the Preferences window, click Git.
    <!-- picture 4 same comment -->
8. In the Name field, type the name you'd like to use for your Git configuration.
    <!-- picture 4 same link-->
9. In the Email field, paste the email address you copied from your GitHub account settings.
    <!-- picture 5 same link -->
10. Click Save.
<!-- picture 6 same link -->

<!--IS THIS PART NECESSARY? HOW IS IT DIFFERENT FROM macOS ? --> 
#### Steps to be followed on Windows:

1. sign in Github.
2. On the upper-right corner of the page, click on your profile photo.
3. Select setting from the Drop-down appeared as a result of the click on profile photo.
   <!-- photo 1. https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/configuring-git-for-github-desktop -->
4. Now in settings click emails.
   <!-- photo 2 same link as in the comment above -->
5. Copy the email address you'd like to use in your local Git configuration.
6. Return to the Github Desktop, Use the file menu, then click on options.
    <!-- picture 3 same comment mac setup-->
7. In the Options window, click Git.
    <!-- picture 4 same comment -->
8. In the Name field, type the name you'd like to use for your Git configuration.
    <!-- picture 4 same link-->
9. In the Email field, paste the email address you copied from your GitHub account settings
    <!-- picture 5 same link -->
10. Click Save.
<!-- picture 6 same link -->




[1]:https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

[2]:https://git-scm.com/downloads
