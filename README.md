# Windows PC for Development Setup
Windows PC Development tools setup

GIT BASH Terminal Installation:

    Download the latest Git For Windows installer.
        https://git-scm.com/download/win
    Install Git For Windows.
        Run Git For Windows Installer.
            Take all defaults during install.
        Reboot PC.
    Verify Git For Windows install.

        Launch and run in GitBash:

        git version

        Verify Git version.


Git requires some configuration before use.

    Configure credentials, required. This may have been done during Git For Windows installation.

        Launch and run in Bash / GitBash:

        git config --global user.name "John Doe"
        git config --global user.email john.doe@johndoe.com

    Configure aliases, optional.

        In Bash / GitBash:

        git config --global alias.br branch
        git config --global alias.co checkout
        git config --global alias.ci commit
        git config --global alias.st status
        git config --global alias.unstage 'reset HEAD --'
        git config --global alias.last 'log -1 HEAD'
        git config --global alias.ll 'log --oneline'

    Verify Git settings change.

        In Bash / GitBash:

        git config --list


TortoiseGit For Windows Installation:

    Download latest TortoiseGit installer:
        https://tortoisegit.org/download/
    Install TortoiseGit.
        Launch TortoiseGit installer.
        In TortoiseGit installer:
            Take all defaults during install.
        Reboot PC.
    Verify TortoiseGit install.
        Launch Windows Explorer:
            Right-click any folder, and check that there is a TortoiseGit context menu extension.
            
  
  
Install Python:

    Download the latest Python installer.
        https://www.python.org/downloads/
        Get version 3.7.0 or newer.
    Install Python.
        Run Python installer.
            Check "Add Python 3.x to PATH".

            For all else, take defaults during install.
        Reboot PC.
    Verify Python install.

        Launch and run in Command Prompt:

        python --version

        Verify Python version.


        
