`git init` : initialize curreent folder as a git repository
 `git status`: tells us what we need to know about our repo
  `git add <FILE>` : adds <FILE> to staging area 
    `git commit: open a text editor
    `git commit -m "Message"`: writes MESSAGE as a commit without a text editor
    `git log`:shows the log (history) of our commits
    `git log --oneline`: shows the shorter oneline commit
    `git diff`: compare current uncommited state with last known git state
      -`git diff`: --stagged`: runs git diff between the staging area and last known state
    `git diff HEAD~<NUMBER>: compares HEAD with commit <NUMBER> ago (relative)
    `git diff <HASH>` : compares HEAD with the commit in <HASH>
