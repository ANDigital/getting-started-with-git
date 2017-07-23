# Getting started with git
This repository is the playground for a git workshop. [Slides for the workshop are available here.](https://docs.google.com/presentation/d/1CYTLwbYDX7joMcOedxpp8_llKvZqMTRpUNuh1CbQ7nA/edit?usp=sharing)

## Install git
* Windows: https://git-for-windows.github.io/
* Mac OS: If not available already, install [Xcode from the Mac Store](https://itunes.apple.com/gb/app/xcode/id497799835)
* Linux: Use your package manager, e.g. `apt-get install git`

## Exercises
1. Clone this repository: ```git clone https://github.com/ANDigital/getting-started-with-git.git```
1. Create a branch with your name: ```git checkout -b <YOUR NAME>```
1. Add yourself to people.json
1. Commit changes: ```git commit -am "add: my name"```
1. Try changing branches: ```git checkout master``` Can you see your changes disappear? Change back to your own branch: ```git checkout <YOUR NAME>```
1. Push your branch to the remote repository: ```git push origin <YOUR NAME>``` _Note that you will need collaborator access to the repository - we should have asked for your Github username at the beginning of the workshop for this._
1. Make a Pull Request from your branch to master on Github

## Further resources
* Workflows: https://www.atlassian.com/git/tutorials/comparing-workflows
* Git documentation: https://git-scm.com/docs
* Gitmojis: https://gitmoji.carloscuesta.me/
* Semantic commit messages: https://seesparkbox.com/foundry/semantic_commit_messages
