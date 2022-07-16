# Members
## Adding new functionality
We will be writing functionality using [Test Driven Development](https://www.agilealliance.org/glossary/tdd/), in which all functionality that can be unit tested should be unit tested.

``Branch naming format: <username>/issue-<issue_number>``
1. Create a new branch according to the issue number
    - If an issue does not exist for your change, create one.
    - ``git branch <branch_name>``
    - ``git checkout <branch_name>``
    - or ``git checkout -b <branch_name>``
    - **Never commit directly to master. All pull requests should be reviewed before merging into master**
1. Only make changes toward the ticket in that branch. If additional functionality needs to be added, make a new ticket or, if related, add info to original ticket.
1. Before a commit can be reviewed, make sure to [add appropriate tests](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/unit-testing.html?highlight=testing) to for the added functionality and make sure these tests are passing. Also make sure your code is appropriately documented, for better readability.
    - Commit messages take the form of ``git commit -m "<type>: <description>"``
    - Current types: feat, doc, fix, test
    - For more information of commit syntax, click [here](https://www.conventionalcommits.org/en/v1.0.0/)
1. After testing and being sure your changes fulfill the ticket, push your changes to the repo and create a merge request to master in github.
1. If there are any comments on your any of your merge requests, make sure to go about completing them and re-pushing so the changes are reflected in the github.
1. When your changes have been accepted, if it hasn't already, merge your changes, and start over for a new issue.
# Non-Members
## Todo: add information on non-member contributions