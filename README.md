![Git to Toggl](https://raw.githubusercontent.com/DJakosa/git-to-toggl/master/image.png)

# Git to Toggl
Git to Toggl is a post commit git hook that takes commit message and adds it to the description of the running time entry in [Toggl](https://www.toggl.com/){:target="_blank"}.

## Prerequisite
* [jq command-line JSON processor](https://stedolan.github.io/jq/){:target="_blank"}

## How to use it
* Put the post-commit file to the `.git/hooks` folder of your local repository.
* Give it a `chmod +x` permission.
* Edit the post-commit file and add your Toggle API key like `API_KEY="your-api-key"`.
* Run new time entry in Toggl.
* The hook will trigger after you create a commit.
* Commit message is appended to the time entry description with delimiter `;`.

## Something does not work?
:)
