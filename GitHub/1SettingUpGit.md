# Seting up Git

### Make a GitHub account

First things first, make sure to create a GitHub account if you do not have one already. Head over to https://github.com/join to create one!

### There are two ways to use git locally on your computer:

- Github CLI
- Github Desktop

## Github CLI

### Installation

#### Windows

You can download the executable from the following page for Microsoft Windows.

Link: https://git-scm.com/download

Once downloaded, follow the on screen prompts to install. As a beginner, it's pretty safe to not change anything and just install the default configuration. Once that is done, you will find a program called _'Git Bash'_ in your Start menu. Congratulations! You've successfully installed Git.

#### MacOS

Assuming you have Homebrew installed and setup, you can go ahead and run:

```sh
brew install git
```

#### Linux

There are quite a few distros out there, and you'll need to use their respective package managers.

- **Ubuntu and derivatives:** `sudo apt install git`

- **Fedora, RHEL based distributions:** ` sudo dnf install git`

- **SUSE based distributions:** `sudo zypper install git`

- **Arch 😎 based distributions:** `sudo pacman -S git`

### Configuring Git CLI

Whether you installed git on Windows, MacOS or Linux, this configuration step is the same!

To begin using GitHub from your local machine, you need to set a username and email address to identify yourself while making commits and what not. To do so, you have to run a couple of commands on your command prompt/terminal.

_Username :_ `git config --global user.name "FIRST_NAME LAST_NAME"`

_E-Mail ID:_ `git config --global user.email "MY_NAME@example.com"`

_NOTE: Make sure to use the same email address that you signed in to GitHub with!_

## Github Desktop

If you want to work with Git locally and you're worried about the command line experience, you can initially download and use the GitHub Desktop interface that provides most of the essential features of GitHub. Download it and follow the onscreen prompts.

_NOTE: Git has to be installed already for GitHub Desktop to work_

Download Github Desktop: https://desktop.github.com
(Download the appropriate version of Github Desktop for your operating system.)

<!-- Is the configuration step for GitHub Desktop really necessary? The whole process is quite user-friendly -->

### Configure Git for Github Desktop:

Github Desktop uses the email address you set in your local Git configuration to connect the commits you make with your account on Github.

### Steps to be followed on Mac:

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

### Steps to be followed on Windows:

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
