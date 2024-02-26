# 1st | First Contributions to acmCSUF

`oss.acmcsuf.com/1st` aims to simplify and guide the way beginners make their
first contribution. If you are looking to make your first contribution, follow
the steps below. If you're not comfortable with command line,
[here are tutorials using GUI tools](https://github.com/firstcontributions/first-contributions/blob/main/README.md#tutorials-using-other-tools).
If you don't have Git on your machine,
[install it](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git).

## Welcome to ACM!

ACM at CSUF provides a social online platform, Discord, that brings passionate
Titans together to engage in multiple conversations regarding our community, the
tech field, and many more. Join
[our Discord server](https://acmcsuf.com/discord) to learn more about future
events, meet new people, and get involved with the community!

## Fork `oss.acmcsuf.com/1st`

<img src="https://github.com/EvanCPSC/1st/assets/142952307/3e78edf3-ce26-4d26-9767-09e012d2a1db" alt="Forking oss.acmcsuf.com/1st visual example" width="800" />

Fork the repository by clicking on the fork button on the top of
[`oss.acmcsuf.com/1st`'s page on GitHub](https://github.com/acmcsufoss/1st).
This will create a copy of this repository in your account.

## Clone the repository

<img src="https://github.com/EvanCPSC/1st/assets/142952307/8c866bcd-8e56-4ebd-be9f-cb597aea2e53" alt="Cloning the github repo visual example" width="800" />

Now clone the forked repository to your machine. Go to your GitHub account, open
the forked repository, click on the code button and then click the _copy to
clipboard_ icon.

Open a terminal and run the following git command: git clone "url you just
copied" where "url you just copied" (without the quotation marks) is the url to
this repository (your fork of this project). See the previous steps to obtain
the url.

<img src="https://github.com/EvanCPSC/1st/assets/142952307/50be2289-a798-441e-8abe-67f618a3eec5" alt="Copy the repo URL visual example" height="400" />

For example:

`git clone https://github.com/this-is-you/acmcsuf.com.git`

where `this-is-you` is your GitHub username. Here you're copying the contents of
the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already
there): `cd acmcsuf.com` Now create a branch using the git switch command:
`git switch -c your-new-branch-name` For example:
`git switch -c add-ethanthatonekid`

## Make necessary changes and commit them

Create a new Markdown file inside `/collaborators` that looks like `gh-user.md`, 
where `gh-user` is your GitHub username. Then, inside that file, include **one** 
line in the following format:

```
[**@your-gh-username**](https://github.com/your-gh-username): Some Description...
```

Replace where it says `your-gh-username` with your GitHub username, so that the 
hyperlink directs to your GitHub profile. Then, add a short description of yourself! 
At the end, it will be rendered in the HTML page with the following format:

<img src="https://github.com/acmcsufoss/1st/assets/112128328/c10d7529-a745-4a8f-9a38-93b832cd52ed" alt="Markdown rendered in HTML page visual example" width="400" />

Please refer to any of the example Markdown files from the list of `/contributors`!

Add those changes to the branch you created using the `git add` command:

```
git add <your-gh-username>.md
```

And commit them with a short description, using the `git commit` command:

```
git commit -m "Added your-gh-username.md"
```

replacing `your-gh-username` with your GitHub username :)

## Push changes to GitHub

Push your changes using the command `git push`:

`git push origin -u add-your-branch-name`

replacing `<add-your-branch-name>` with the name of the branch you created
earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request`
button. Click on that button.

<img src="https://github.com/EvanCPSC/1st/assets/142952307/a3ed5a0a-eccf-4435-85b1-257eb3d38ab5" alt="Compare and pull request visual example" width="800" />

Now submit the pull request.

<img src="https://github.com/EvanCPSC/1st/assets/142952307/5e500e80-022e-4881-8b81-ac963e238116" alt="Creating the pull request visual example" width="800" />

Soon, someone will be merging all your changes into the master branch of this
project. You will get a notification email once the changes have been merged.

---

### CONGRATULATIONS ON MAKING YOUR FIRST CONTRIUBUTION

Inspired by
[First Contributions](https://github.com/firstcontributions/first-contributions#readme)

Maintained with 💚 by [**@acmcsufoss**](https://github.com/acmcsufoss)
