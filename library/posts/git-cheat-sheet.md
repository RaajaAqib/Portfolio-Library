# GIT CHEAT SHEET
Git is the free and open source distributed version control system that's responsible for everything GitHub-related that happens locally on your computer. This cheat sheet features the most important and commonly
used Git commands for easy reference.

## INSTALLATION & GUIS
With platform-specific installers for Git, GitHub also provides the
ease of staying up-to-date with the latest releases of the command
line tool while providing a graphical user interface for day-to-day
interaction, review, and repository synchronization.

## SETUP
Configuring user information used across all local repositories

 ### git config --global user.name “[firstname lastname]”
Set a name that is identifiable for credit when reviewing version history

 ### git config --global user.email “[valid-email]”
 Set an email address that will be associated with each history marker


 ### git config --global color.ui auto
 Set automatic command line coloring for Git for easy reviewing

## SETUP & INIT
Configuring user information, initializing, and cloning repositories

 ### git init
initialize an existing directory as a Git repository


### git clone [url]
retrieve an entire repository from a hosted location via URL

## STAGE & SNAPSHOT
Working with snapshots and the Git staging area

### git status
show modified files in working directory, staged for your next commit

### git add [file]
Add a file as it looks now to your next commit (stage)

### git reset [file]
unstage a file while retaining the changes in the working directory


### git diff
diff of what is changed but not staged

### git diff --staged
diff of what is staged but not yet committed

### git commit -m “[descriptive message]”
Commit your staged content as a new commit snapshot

## BRANCH & MERGE
Isolating work in branches, changing context, and integrating changes

### git branch
List your branches. a * will appear next to the currently active branch

### git branch [branch-name]
Create a new branch at the current commit

### git checkout
switch to another branch and check it out into your working directory

### git merge [branch]
merge the specified branch’s history into the current one

### git log
show all commits in the current branch’s history

:::note
Use Flow Designer for orchestration logic.
:::

:::warning
Avoid using Business Rules for approvals.
:::

:::tip
Always log execution paths during debugging in Washington.
:::

:::info
Always log execution paths during debugging in Washington.
:::

:::important
Always log execution paths during debugging in Vancouver.
:::


## Version Differences

<!-- ![Approval step configuration in Flow Designer](./photo's/flow-designer/Tenses.png) -->






<figure class="doc-image">
  <img src="./Pictures/flow-designer/Aqib.png"
       alt="Approval step configuration in Flow Designer"
       loading="lazy">
  <figcaption>Approval step configuration in Flow Designer</figcaption>
</figure>
