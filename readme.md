# CSSA Hackathon Project Submissions
Welcome to the CSSA 2022 Hackathon!
To organise our submissions and ensure voting is both smooth and accessible, we will be requesting that everybody submit their projects to a group repository (if they wish to have it graded).
Since we understand that having a group repo for the actual code will be, well, nightmarish to manage, we'll just be asking that people submit a file describing their project, and providing some metadata and info that we can use. You will be able to [vote using this form](https://forms.office.com/r/3iMqNKGy6i).

To that end:
## CSSA Hackathon Repo
The hackathon repo is available at [github.com/anucssa/hackathon-submissions-2022](https://github.com/anucssa/hackathon-submissions-2022).
You can push to it, by creating a fork, applying your changes there and then creating a pull request. You can do this via the web interface if you do not have git installed.
If you don't know how to use git, reach out to one of our friendly comittee members or CROs and we'll be able to lend a hand!

## Submission Format
You should create a file in [/submissions](https://github.com/anucssa/hackathon-submissions-2022/tree/main/submissions) that is named as either `<githubusername>.json` or `<githubusername>.yml` where `<githubusername>` is replaced with your GitHub username. (Hopefully we'll be able to use this to automate PRs). Where you have multiple people in your group just choose one name and include the other authors in the yml or json file.
This file should contain the following attributes:
| Property       | Description                                                                                                                                                                                                      | Required?                        |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| name           | The name of your submission or project.                                                                                                                                                                          | Yes                              |
| author         | Your name, or a pseudonym that you would like to use instead.                                                                                                                                                    | No, defaults to GitHub username. |
| license        | The license you would like to use for your code.                                                                                                                                                                 | No                               |
| repository_url | The repository that contains your source code.                                                                                                                                                                   | Yes                              |
| demo_url       | A demo of your project that people can use to evaluate it, as either a video of you using it, instructions to use it, a web link to the project, or some other easily accessible format.                         | Yes                              |
| tags           | An array of tags that you can apply to your project, to help us categorise projects using similar things for people to find them. Feel free to tag things like langauges, themes, technologies, frameworks, etc. | No                               |

You can see an example of both types of file in the submissions folder, under [example.json](https://github.com/anucssa/hackathon-submissions-2022/blob/main/submissions/example.json) and [example.yml](https://github.com/anucssa/hackathon-submissions-2022/blob/main/submissions/example.yml).
These files will be read with a YAML parser, but JSON is a subset of YAML so it should work fine in either case.
Once you create a submission file, create a pull request to merge it into the `main` branch and we'll approve it!
