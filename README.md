# all-about-interview

We study data structure, algorithm, and programmning problems

## Book

`Cracking the coding interview` written by Gayle Laakmann McDowell

## What we're going to do in this study

1. `Solve` the problems in each chapter of the book.
2. `Commit` the solutions to each member's remote repository. (@member_id/all-about-interview)
3. Create a `Pull Request` to the upstream repository (cs-sprout/all-about-interview)
4. `Review` the code pull requested by other members.
5. After review, `Merge the code to the upstream repository.

## How to collaborate with a 'Forking-Workflow'

Forking-Workflow is one way to collaborate with git.

### Pre-requsite

1. Fork this repository `cs-sprout/all-about-interview` to your personal repository `@member_id/all-about-interview`
  - From now on
    + `cs-sprout/all-about-interview` will be called `upstream` repository.
    + `@member_id/all-about-interview` will be called `origin` repository.
2. Clone your origin repository to your local storage
  - `git clone https://github.com/@member_id/all-about-interview.git`
3. Connect your local storage to upstream repository
  - `git remote add upstream https://github.com/cs-sprout/all-about-interview.git`
4. Create a branch where you will work.
  - `git checkout -b branch_name`

### Forking-workflow

1. Before starting work, please pull the upstream repository first.
  - `git pull upstream master`
2. Work in the branch you added.
  - you can change current branch by `git checkout branch_name`.
3. After finishing work, push your work to your origin repository.
  - `git commit -a -m "write commit messages"`
  - `git push origin [branch_name]`
4. Go to the github origin repository page and create a Pull Request to the upstream repository.
5. Review the Pull Requested code which other members created
  - Read the code and add comments, questions or suggestions etc.
7. After checking the review, edit the code if you need.
8. Merge the code to the upstream repository.

### Reference

- [English Reference](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)
- [Korean Reference](https://andamiro25.tistory.com/193)
