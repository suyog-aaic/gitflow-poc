mvn gitflow:release-start --->

Checking out 'develop' branch.
Checking for SNAPSHOT versions in dependencies.
What is release version? [0.0.0]: 0.0.2
Creating a new branch 'release/0.0.2' from 'develop' and checking it out.
Updating version(s) to '0.0.2'.
Committing changes.


mvn gitflow:release-finish  --->

[INFO] Checking for uncommitted changes.
[INFO] Checking out 'release/0.0.2' branch.
[INFO] Checking for SNAPSHOT versions in dependencies.
[INFO] Fetching remote from 'origin'.
[INFO] Fetching remote from 'origin'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'main' with remote 'origin/main'.
[INFO] Checking out 'release/0.0.2' branch.
[INFO] Cleaning and testing the project.
[INFO] Checking out 'main' branch.
[INFO] Merging (--no-ff) 'release/0.0.2' branch.
[INFO] Creating '0.0.2' tag.
[INFO] Checking out 'develop' branch.
[INFO] Merging (--no-ff) '0.0.2' branch.
[INFO] Updating version(s) to '0.0.3-SNAPSHOT'.
[INFO] Committing changes.
[INFO] Pushing 'main' branch to 'origin'.
[INFO] Pushing 'develop' branch to 'origin'.
[INFO] Deleting remote branch 'release/0.0.2' from 'origin'.
[WARNING] There were some problems deleting remote branch 'release/0.0.2' from 'origin'.
[INFO] Deleting 'release/0.0.2' branch.