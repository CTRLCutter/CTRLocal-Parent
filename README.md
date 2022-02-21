# CTRLCutter Parent Project

Repository for the parent project of the local repos from the CTRLCutter project.

## Usage

Since this repo features different submodules use the *--recursive* modifier when you use the clone command.

Just like this. *git clone --recursive https://github.com/CTRLCutter/CTRLocal-Parent.git*

Then you can use the subrepos just like normal repos.
Don't forget to update this repo and their submodule references, since they will then just point to previous commits.

You can do this just as you would commit any other repo.
- git add .
- git commit -m "Submodule Update"
- git push