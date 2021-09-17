# What Are Workflows?

Workflow files define the automated procedure that takes place when triggered by an event.

Workflows are made up of one or more jobs.

Jobs are made up of an environment (called a Runner) and one or more tasks called a steps.

Runners are the virutal server used to execute your tasks.  You can use GitHub-hosted runners, or host your own runners by installing the GitHub Actions runner application on your machines.

Steps are either *actions* or shell commands

Actions are self contained units of work.  These are the smallest portable part of GitHub Actions.  Actions are easy to share and can be created by anyone!