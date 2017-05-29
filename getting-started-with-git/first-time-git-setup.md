[//]: # (Essential configuration: username and email variables)

# First-time Git Setup

## Configure Git
After installing Git check that is is working by opening the CLI and entering `git --version`. This displays the version of Git installed on your OS. If no (or incorrect) output is produced, then probably Git is not well-configured in your system.

##### Identity
`git config --global user.name <username>`

&emsp;&emsp; This command sets up the username of your Git profile. Preferably set this to the username of your remote version control repository host (whether [Github](github.com), [bitbucket](bitbucket) or other from this [list](https://en.wikipedia.org/wiki/Comparison_of_source_code_hosting_facilities))

`git config --global user.email <email>`

&emsp;&emsp; This command sets up the email of your Git profile. Preferably set this to the email you used in setting up your remote version control repository.

