# Getting Started

## Logistics

This project is worth 8% of your overall grade in the class.

* Part 1 is due **Sunday, 11/22/2020 at 11:59PM PST (GMT-8)** and will be worth 24% of your score. Your score will be determined by public tests only.
* Part 2 is due **Wednesday, 12/2/2020 at 11:59PM PST (GMT-8)** and will be worth the remaining 76% of your score. We'll be running the public tests for Part 2 and all hidden tests for both Part 1 and Part 2 on this submission.

The workload for the project is designed to be completed solo, but this semester we're allowing students to work on this project with a partner if you want to. Your partner does not have to be the same as the one you had for previous assignments. Feel free to search for a partner on [this Piazza thread](https://piazza.com/class/kducz9b1i3h78i?cid=5)!

## Prerequisites

You should watch all the recovery lectures \(lectures 16, 17, and 18\) before starting this project. We also highly recommend reviewing the [recovery notes](https://cs186berkeley.net/resources/static/notes/n12-Recovery.pdf).

## Fetching the released code

Complete [this form](https://forms.gle/HFBF9evuhqriL6Cf9) to get a Github Classroom link. Once your private repo is set up clone the Project 5 skeleton code onto your local machine.

### Setting up your local development environment

If you're using IntelliJ you can follow the instructions [in Project 0](../proj0/getting-started.md#setting-up-your-local-development-environment) in to set up your local environment again. Once you have your environment set up you can head to the next section [Your Tasks](../proj2/your-tasks.md) and begin working on the assignment.

## Adding a partner

Once you've found a partner fill out [**this form**](https://forms.gle/HFBF9evuhqriL6Cf9) so we know who you're working with. If you want to share code over GitHub you can follow the instructions [here](../../common/adding-a-partner-on-github.md).

## Debugging Issues with GitHub Classroom

Feel free to skip this section if you don't have any issues with GitHub Classroom. If you are having issues \(i.e. the page froze or some error message appeared\), first check if you have access to your repo at `https://github.com/berkeley-cs186-student/fa20-proj5-username`, replacing `username` with your GitHub username. If you have access to your repo and the starter code is there, then you can proceed as usual. If you have access to your repo but the starter code is not there, run the following commands in a terminal \(again replacing `username` with your GitHub username\):

```text
git clone https://github.com/berkeley-cs186/fa20-moocbase fa20-proj5
cd fa20-proj5/
git remote remove origin
git remote add origin https://github.com/berkeley-cs186-student/fa20-proj5-username.git
git push -u origin master
```

Then, you can proceed as usual.

### 404 Not Found

If you're getting a 404 not found page when trying to access your repo, make sure you've set up your repo using the GitHub Classroom link in the Project 2 release post on [Piazza](https://piazza.com/class/).

If you don't have access to your repo at all after following these steps, feel free to contact the course staff on Piazza.

