# mc-exercise
Where it went wrong:
After Carol ACP’d, created pull request,  and Alice and Ted accepted it. Ted cloned the merged master branch into Ted’s computer ONLY.
Bob did not pull from master branch after after Carol pushed. This meant that Bob was not up-to date on Carol and Bob’s work. Merge conflicts ensued.
Bob and Carol’s team had worked in parallel with Alice and Ted’s then both teams ACP’d and made pull requests. Merge conflicts ensued.
Ultimately, we had to resolve conflicts manually, which would not scale up in a larger project.
This could have been prevented by clear communication on when a team or individual ACPs, then everyone on the project can do a pull request to stay up to date. It can be easier when people are not working on the same lines of code to avoid these conflicts. For our project, I propose that whenever one of us wants to push to master, everyone says “got it (or whatever), then we all pull to our local directories.

