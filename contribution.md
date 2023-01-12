# Contributing

Thank you for considering and taking the time to contribute! Our aim to help people get started with Open-source technologies and upskilling.

The following are guidelines for contributing to this project.

## How to Add Communities, OSS Projects

Please open a [new issue ](https://github.com/DIEMS-HUB/Roadmaps/issues/new)in the appropriate GitHub repository and mention the community/ oss project you want to add with all the required links. Once approved by the maintainers you can go ahead and create a [Pull request](https://github.com/DIEMS-HUB/Roadmaps/pulls) regarding the same.

Make sure you move to correct roadmap and respective folder of your addition. Add your approved community oss project in alphabetical order only. Thank You.

## How to Contribute

- Take a look at the Existing issues or create your own!
- Fork the Repo and create a Branch for any Issue that you are working upon.
- Create a Pull Request which will be promptly reviewed and suggestions would be added to improve it.
- Add Screenshots to help us know what this is all about.

## How to make a Pull Request

**1.** Fork the repository by clicking at the top right corner.

**2.** Clone the forked repository.
```
   git clone https://github.com/DIEMS-HUB/Roadmaps.git
```

**3.** Navigate to the project directory.
```
   cd DIEMS-HUB
```

**4.** Create a new branch:
```
   git checkout -b YourBranchName
```

**5.** Make changes in source code.

**6.** Stage your changes and commit

```
   git add .
   git commit -m "<your_commit_message>"
```

**7.** Push your local commits to the remote repo.

```
   git push origin YourBranchName
```

**8.** Create a [PR](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

**Note** If anyone contributes to this repository, then the changes will not be reflected in your local repository. For that:

**9.** Setup a reference(remote) to the original repository to get all the changes from the remote.
```
   git remote add upstream  https://github.com/DIEMS-HUB/Roadmaps.git
```

**10.** Check the remotes for this repository.
```
   git remote -v
```

**11.** Fetching from the remote repository will bring in its branches and their respective commits.
```
   git fetch upstream
```

**12.** Make sure that you're on your master branch.
```
   git checkout master
```

**13.** Now that we have fetched the upstream repository, we want to merge its changes into our local branch. This will bring that branch into sync with the upstream, without losing our local changes.
```
   git merge upstream/master
```

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)













