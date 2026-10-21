
# Jenkins-practice
# Webhook test

# Jenkins GitHub Webhook Practice

## Objective
To understand how a Git push automatically triggers a Jenkins job using a GitHub webhook.

## Tools Used
- Git
- GitHub
- Jenkins
- Ubuntu on WSL
- ngrok

## Files
- `README.md` - Project documentation
- `app.sh` - Bash script executed by Jenkins

## What I Implemented
1. Created a GitHub repository.
2. Added and pushed a Bash script to GitHub.
3. Configured a Jenkins Freestyle job to clone the repository.
4. Added a shell build step to execute `app.sh`.
5. Configured a GitHub webhook to trigger Jenkins on a push.
6. Verified that a code push automatically started a Jenkins build.

## Workflow
Developer pushes code to GitHub -> GitHub sends a webhook -> Jenkins checks out the repository -> Jenkins executes the Bash script -> Build result is displayed in Console Output.

## Result
Successfully tested GitHub and Jenkins integration and verified automatic build triggering.
