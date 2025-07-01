[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/iemafzalhassan/first-contributions-practice/badges/users.svg)](https://www.codetriage.com/iemafzalhassan/first-contributions-practice)

# First Contributions Practice

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Fork this repository

Fork this repository by clicking on the fork button on the top of [this page](https://github.com/iemafzalhassan/first-contributions-practice).
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button, then on SSH tab and then click the _copy url to clipboard_ icon.

Open a terminal and run the following git command:

```sh
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```sh
git clone git@github.com:your-github-username/first-contributions-practice.git
```

where `your-github-username` is your GitHub username. Here you're copying the contents of the first-contributions-practice repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```sh
cd first-contributions-practice
```

Now create a branch using the `git switch` command:

```sh
git switch -c your-new-branch-name
```

For example:

```sh
git switch -c add-alonzo-church
```

**If you get any errors using git switch, click here:**

If the error message "Git: `switch` is not a git command. See `git –help`" appears, it's likely because you're using an older version of git.

In this case, try to use `git checkout` instead:

```sh
git checkout -b your-new-branch-name
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```sh
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```sh
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```sh
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

**If you get any errors while pushing, click here:**

- ### Authentication Error

  ```sh
  remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/iemafzalhassan/first-contributions-practice.git/'
  ```

  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

  Also, you might want to run 'git remote -v' to check your remote address.

  If it looks anything like this:

```sh
  origin	https://github.com/iemafzalhassan/first-contributions-practice.git (fetch)
origin	https://github.com/iemafzalhassan/first-contributions-practice.git (push)
```

change it using this command:

```sh
  git remote set-url origin git@github.com:iemafzalhassan/first-contributions-practice.git
```

  Otherwise you'll still get prompted for username and password and get authentication error.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers!

If you'd like more practice, you can look for other beginner-friendly repositories to contribute to.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on.

## Tutorials Using Other Tools

| [GitHub Desktop](docs/gui-tool-tutorials/github-desktop-tutorial.md) |
| --- |

*More GUI tool tutorials coming soon! Feel free to contribute tutorials for other tools.*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the original [first-contributions](https://github.com/firstcontributions/first-contributions) project
- Thanks to all contributors who help make this project better