# testGitVerifiedSignature
used to test git verified commits
Link to learn verified commits := https://help.github.com/en/github/authenticating-to-github

When committing changes in your local branch, add the -S flag to the git commit command:
$ git commit -S -m your commit message
# Creates a signed commit
If you're using GPG, after you create your commit, provide the passphrase you set up when you generated your GPG key.
When you've finished creating commits locally, push them to your remote repository on GitHub:
$ git push
# Pushes your local commits to the remote repository
On GitHub, navigate to your pull request.
On the pull request, click  Commits.
Commits tab on a pull request
To view more detailed information about the verified signature, click Verified.
Signed commit

#requirements
Gnupg software