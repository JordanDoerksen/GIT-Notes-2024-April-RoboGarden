# GIT Notes - 2024 April RoboGarden

> Some notes on GIT and GIT usage

## Terms

| Term              | Description                                                                            |
| ----------------- | -------------------------------------------------------------------------------------- |
| Repository (repo) | The collection of code and its history regardless of where it lives (remote/local)     |
| branch            | A separate version of your project that is being developed alongside other branches    |
| merge             | The process of taking changes from one branch and copying them to another branch       |
| commit            | Add staged files into the local git history on the current branch                      |
| untracked         | A file that git is not tracking or ignoring for some other reason                      |
| staged            | A tracked file that has changes since its last commit and is ready for the next commit |


## Commands

| Command                                                   | Usage                                                                                                           |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| `git init`                                                | Creates a git repository in the current directory                                                               |
| `git status`                                              | Display information about the current status of the git repository located in the current or parent directories |
| `git add <file name>`                                     | Stage a file to be committed                                                                                    |
| `git commit -m "<commit message>"`                        | Commits a file to the local (.git) repository                                                                   |
| `git restore <file name>`                                 | Restores a file to match the most recent commit                                                                 |
| `git diff <file name>`                                    | Shows changes to file since last commit                                                                         |
| `git blame <file name>`                                   | Shows who did what and when                                                                                     |
| `git remote add origin <path_to_upstream_repository.git>` | Adds a git repository to be used as the upstream (authoritative) source                                         |
| `git push`                                                | Copy all changes from local repository to upstream repo                                                         |
| `git fetch`                                               | Get information about the upstream repository                                                                   |
