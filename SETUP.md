# Getting Started

Complete the following before the first class:

- [ ] Take the [**Student Survey**](https://virginia.az1.qualtrics.com/jfe/form/SV_799Osj0KfAPPJ7E).

### Services

- [ ] Create a [**GitHub**](https://github.com/) account if you do not already have one.
- [ ] Create an [**AWS Account**](https://signin.aws.amazon.com/signup?request_type=register). This requires payment for any services used. I recommend buying a prepaid credit card ($50-$100 max) and using it to create your new Amazon Web Services account with the “Free Tier.” This course should incur $30-40 of charges at the most.
- [ ] Create a free [**Docker account**](https://app.docker.com/signup) to use with Docker Desktop.

### Software

- [ ] <img src="https://icons.iconarchive.com/icons/martz90/circle/128/apple-2-icon.png" width="24" height="24"> MacOS users: Find the **Terminal** app (in Applications --> Utilities). You may want to add it to your dock.
- [ ] <img src="https://icons.iconarchive.com/icons/martz90/circle/128/windows-8-icon.png" width="24" height="24"> Windows users: [**Install and set up WSL**](https://learn.microsoft.com/en-us/windows/wsl/install), the Windows Subsystem for Linux. The default WSL installation will create an Ubuntu environment for you. The username and password you create within WSL does not have to match your Windows username/password. Be sure to complete the WSL installation before you install VS Code.
- [ ] Install [**Docker Desktop**](https://www.docker.com/get-started/) on your laptop and sign in using the Docker account you created above.
- [ ] Install [**VS Code**](https://code.visualstudio.com/), the free IDE (integrated development environment), in your primary OS. (That is, Windows users install VS Code on the Windows side.) Windows users, once you install VS Code you should install the WSL plugin when prompted.
- [ ] Install the [**`git` command line**](https://git-scm.com/downloads) for your OS. Windows users may want to install it both in Windows and within WSL. 
- [ ] Install [**`jq`**](https://jqlang.github.io/jq/) for your OS.

### Python

- [ ] Find Python3 on your laptop. Version 3.9 or higher is preferable. You should be able to invoke it interactively from your terminal with:

        $ python3

    If you do not have Python installed, then:

- [ ] <img src="https://icons.iconarchive.com/icons/martz90/circle/128/apple-2-icon.png" width="24" height="24"> MacOS users can install from [Pytyon.org](https://www.python.org/downloads/) or by using `homebrew`.
- [ ] Windows users can install from [Python.org](https://www.python.org/downloads/) to run within Windows.
- [ ] Windows users will primarily develop within WSL, where you can install Python3 with:

        $ sudo apt update
        $ sudo apt install python3 python3-pip

    Once you have a working version of Python on your laptop you need to point VS Code to it. Try creating a sample Python project and making this connection yourself.
