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



mvn gitflow:release  --->

[INFO] --- gitflow:1.20.0:release (default-cli) @ Calculator ---
[INFO] Checking for uncommitted changes.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'develop' with remote 'origin/develop'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'main' with remote 'origin/main'.
[INFO] Checking out 'develop' branch.
[INFO] Checking for SNAPSHOT versions in dependencies.
[INFO] Cleaning and testing the project.
What is release version? [0.0.3]: 0.0.3
[INFO] Updating version(s) to '0.0.3'.
[INFO] Committing changes.
[INFO] Checking out 'main' branch.
[INFO] Merging (--no-ff) 'develop' branch.
[INFO] Creating '0.0.3' tag.
[INFO] Checking out 'develop' branch.
[INFO] Merging (--no-ff) '0.0.3' branch.
[INFO] Updating version(s) to '0.0.4-SNAPSHOT'.
[INFO] Committing changes.
[INFO] Pushing 'main' branch to 'origin'.
[INFO] Pushing 'develop' branch to 'origin'.


mvn gitflow:feature-start --->

[INFO] Checking for uncommitted changes.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'develop' with remote 'origin/develop'.
What is a name of feature branch? feature/: test
[INFO] Creating a new branch 'feature/test' from 'develop' and checking it out.
[INFO] Updating version(s) to '0.0.4-test-SNAPSHOT'.
[INFO] Committing changes.

mvn gitflow:feature-finish   --->
Feature branches:
1. feature/test
Choose feature branch to finish (1) 1: : 1
[INFO] Fetching remote from 'origin'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'develop' with remote 'origin/develop'.
[INFO] Checking out 'feature/test' branch.
[INFO] Cleaning and testing the project.
[INFO] Updating version(s) to '0.0.4-SNAPSHOT'.
[INFO] Committing changes.
[INFO] Checking out 'develop' branch.
[INFO] Merging (--no-ff) 'feature/test' branch.
[INFO] Pushing 'develop' branch to 'origin'.
[INFO] Deleting remote branch 'feature/test' from 'origin'.
[WARNING] There were some problems deleting remote branch 'feature/test' from 'origin'.
[INFO] Deleting 'feature/test' branch.
mvn gitflow:hotfix-start  --> 
Checking for uncommitted changes.
[INFO] Checking out 'main' branch.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'main' with remote 'origin/main'.
What is the hotfix version? [0.0.4]: 0.0.5
[INFO] Creating a new branch 'hotfix/0.0.5' from 'main' and checking it out.
[INFO] Updating version(s) to '0.0.5'.
[INFO] Committing changes.




mvn gitflow:hotfix-finish ---> 
Fetching remote from 'origin'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'develop' with remote 'origin/develop'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'main' with remote 'origin/main'.
[INFO] Fetching remote from 'origin'.
[INFO] Checking out 'hotfix/0.0.5' branch.
[INFO] Cleaning and testing the project.
[INFO] Checking out 'main' branch.
[INFO] Merging (--no-ff) 'hotfix/0.0.5' branch.
[INFO] Creating '0.0.5' tag.
[INFO] Checking out 'develop' branch.
[INFO] Updating version(s) to '0.0.5'.
[INFO] Committing changes.


mvn gitflow:support-start 

[INFO] Creating a new branch 'support/0.0.2' from '0.0.2' and checking it out.
[INFO] Pushing 'support/0.0.2' branch to 'origin'.



aaic@AAICs-MacBook-Pro gitflow-poc % mvn gitflow:release       
[INFO] Scanning for projects...
[INFO] 
[INFO] -----------------------< com.houari:Calculator >------------------------
[INFO] Building Calculator 0.0.5
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- gitflow:1.20.0:release (default-cli) @ Calculator ---
[INFO] Checking for uncommitted changes.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'develop' with remote 'origin/develop'.
[INFO] Fetching remote from 'origin'.
[INFO] Comparing local branch 'main' with remote 'origin/main'.
[INFO] Checking out 'develop' branch.
[INFO] Checking for SNAPSHOT versions in dependencies.
[INFO] Cleaning and testing the project.
What is release version? [0.0.5]: 1.0.1
[INFO] Updating version(s) to '1.0.1'.
[INFO] Committing changes.
[INFO] Checking out 'main' branch.
[INFO] Merging (--no-ff) 'develop' branch.
[INFO] Creating '1.0.1' tag.
[INFO] Checking out 'develop' branch.
[INFO] Merging (--no-ff) '1.0.1' branch.
[INFO] Updating version(s) to '1.0.2-SNAPSHOT'.
[INFO] Committing changes.
[INFO] Pushing 'main' branch to 'origin'.
[INFO] Pushing 'develop' branch to 'origin'.
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  28.023 s
[INFO] Finished at: 2023-10-20T15:03:32+05:30



gitflow:release
mvn gitflow:support-start
mvn gitflow:version-update -DpushRemote=true
