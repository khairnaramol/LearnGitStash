clone - get local copy from server link ( git clone <link>)
  stage :- git add adds the files into staging area
  working area: file has some changes goes into working area
  local Repo: after commit files moved to local repo
  push : send files to remote GitHub server
  
  Move files from stag to working area commands ( revert changes locally)
  git reset filename / .
  git clean -f 
  
  Revert changes which are commited (locally)
  git revert commitid ( best practice to use this)
  or git reset  --mixed/--soft/--hard head^
  
  
  see commit history use below command
  git log 
