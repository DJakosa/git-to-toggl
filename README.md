# Git to Toggle
Git to Toggle is a post commit git hook that takes commit message and adds it to the description of the running time entry in Toggl.

## How to use it
* Put the post-commit file to the `.git/hooks` folder of your local repository.
* Give it a `chmod +x'` permission.
* Edit the post-commit file and add your Toggle API key like `API_KEY="your-api-key`.
* The hook will trigger after you create a commit.
* Commit message is appended to the time entry description with delimiter `;`.

## Something does not work?
:)
