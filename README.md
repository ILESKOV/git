# git
rules

PEFECT COMMIT

THE PERFECT COMMIT MESSAGE
1) Subject = consice summary of what happened
2) Body = more detailed explanation
      -What is now different than before?
      -What's the reason for the change?
      -Is there anything to watch out for/ anything particularly remarkable?
      
git status                 ----> Status
git add <filename>         ----> Add file
git add -A                 ----> Add all files
git diff <filename>        ----> See changes in file
git add -p <filename>      ----> add patch level waht to include and what not  (to choose y for YES and no for NO)
export GIT_EDITOR="subl . --wait --new-window"      ---> This way we can add editor
git commit                 ----> and we can use this editor to write message with body
git commit - m "message"   ----> commit with message
git log                    ----> log commits
  


  
  
BRANCHING STRATEGIES
  
  A WRITTEN CONVENTION
  
Agree on a Branching Workflow in Your Team
  
  1) Git allows you to create branches - but it doesn't tell you how to use them!
  2) You need a written best practise of how work is ideally structured in your team - to avoid mistakes & collisions.
  3) It highly depends on your team / team size, on your project, and how you handle releases.
  4) It helps to onboard new team members("this is how we work here").
  
Integrating Changes & Structuring Releases
  
  1) Mainline Development ("Always Be Integrating")
     This is how it looks:
     -- few branches
     -- relatively small commits
     -- high-quality testing & QA standarts
  
  2) State, Release, and Feature Branches (Branches Enhance Structures & Workflows)
     -- different types of branches...
     -- ...fulfill different types of jobs
  
  TWO MAIN TYPES OF BRANCHES --> Long running & Short-Lived Branches
   
  1) LONG RUNNING
     -- exist through the complete lifetime of the project
     -- often, they minor "stages" in your dev life cycle
     -- common convention: no direct commits!
  
  2) SHORT-LIVED
     -- for new features, bug fixes, refactorings, experiments...
     -- will be deleted after integration (merge/rebase)
     -- common convention: no direct commits!
  
  TWO EXAMPLE BRANCHING STRATEGIES
  
  1)GitHub Flow
     -- very simple, very lean: only one long running branch ("main") + feature branches
  2)GitFlow
     -- more structure, more rules
     -- long running: "main" + "develop"
     -- short-lived: features, releases, hotfixes
  
  
  THE "BEST" BRANCHING MODEL??
     -- consider your project, release cycle, and team
     -- take inspiration from existing models(like "GitFlow" or "GitHub Flow")
     -- ..and create your own model!
     
  
