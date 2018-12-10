Guideline to contribute to the website
--------------------------------------

- We accept PRs only on `develop` branch. No PRs shall be accepted on `master` branch.

- We prefer small feature changes instead of bulk changes. That makes it easier for both the developer as well as reviewer. Smaller requests would have a faster turn-around time in the review-response cycle.

Workflow
--------

If you're new to git version control system, please follow these guidelines:

- Fork the repo.
- Clone your fork.
- Add upstream remote.
- Now create a feature branch, like `git checkout -b <feature-name>`.
- Start working on the issue. Commit early; commit often.
- Open up a Pull Request with base branch as `develop` and compare branch as `feature-branch` of your fork.
- Once you get review, address those in next commits. If you get `LGTM` (Looks Good To Me) tag on your PR, it's 
time to get your PR merged. Congrats. 
- Last step is to just squash all your commits into one and briefly describe what you did. (Most of the time, the reviewer shall do this for you, but it would be good if you do it by yourself.)
- After squashing, you need to force push to your feature branch.
- Once your PR is merged, it's time to delete the feature branch from your fork. Optional, though.
- Since the master/develop of the original project may be ahead now, it's time to pull the changes from the 
upstream and update on your fork.
- Now for next feature, repeat!

Happy Contributing! :D
