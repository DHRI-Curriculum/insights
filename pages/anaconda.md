![Header image for Keeping your Anaconda installation up to date](images/header-anaconda.png)

# Keeping your Anaconda installation up to date

From time to time, and especially before you start working on a new project or when you are running into unexpected issues, you're going to want to make sure that your Anaconda installation and its packages are up to date. Through software and package updates developers implement new functionalities, usability improvements, ensure compatibility with other software, and especially patch known coding flaws.

## How to check your current version of Anaconda

Whether knowing your current version of Anaconda alone is not enough information to determine whether your software needs to be updated, it is a useful piece of information to have in handy when troubleshooting an issue or asking for support.

### MacOS

1. Click the Spotlight Search button (the magnifying glass) in the top right of your desktop.

2. Type `terminal` into the bar that appears.

3. Select the first item that appears in the list.

4. When the Terminal pops up, you will likely see either a window with black text over white background or colored text over a black background.

5. In your Terminal, type `conda --version` and press enter.

    The output of your query will tell you which version of Anaconda is installed on your computer. _E.g._, `conda 4.7.12`

### Windows

1. Look for Git Bash in your programs menu and open.

2. If you can't find the git folder, just type `git bash` in the search box and select `git bash` when it appears.

3. Open the program.

4. When the terminal pops up, you will likely see either a window with black text over white background or colored text over a black background.You know you're in the right place when you see the `$`.

5. In your terminal, type `conda --version` and press `Enter`.

    The output of your query will tell you which version of Anaconda is installed on your computer. _E.g._, `conda 4.7.12`

## How to make sure you have the current version of Anaconda installed

To access your terminal, follow the steps for your operating system above. Once inside your terminal, type `conda update -n root conda` and press <kbd>enter</kbd>. Your computer will then retrieve from the web the latest version of Anaconda and install it in your selected environment.

## Making sure all Python packages are up-to-date in your Anaconda installation

To access your terminal, follow the steps for your operating system above. Once inside your terminal, type `conda update --all` and press <kbd>enter</kbd>.

This command will update all packages in the current environment to the latest version.
