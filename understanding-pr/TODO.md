
Instructions for completing this assignment

1. If you haven't already, [fork](https://github.com/dbroudy/command-line-fun/fork) this project to create your own copy in your account. This will allow you to save your work. The [forking workflow](https://guides.github.com/activities/forking/) is one of the main ways that people collaborate on GitHub and other git repositories.
1. Clone your fork. Substitute your user name below, or copy the whole url from your repo.
    ```
    git clone git@github.com:yourusername/command-line-fun.git
    ```
1. Create a branch in your repository.
    ```
    git checkout -b assigment-1
    ```
    Each assignment you do should be in a different branch. Keeping the master branch in sync with the upstream repository allows you to get new assignments, and a branch for each assignment will allow you to submit clean PRs with just the changes related to that assignment.
1. Edit the hello.txt file to add the text `world` after the `hello` using the text editor of your choice (nano is a simple command line editor that is included in many systems). The final result is the file should say `hello world`
1. Save your work to your repository by commiting and pushing:
    ```
    git commit
    git push
    ```
    Commit create a version in your local git repository
    Push sends all the changes in your local git to the remote git on GitHub.
1. Create a [Pull Request (PR)](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) back to the main repository.
1. Usually, when you create a PR, the goal is to contribute to the original project. In this case, it's a way of letting me know that you've done the assignment and want feedback. I'll comment and approve your PR! But I won't actually merge it, because then the answers would be part of the main repository, and that wouldn't be any fun.

## Extra Credit
Anything confusing about this assigment? Submit a PR with changes to make it clear for other students!