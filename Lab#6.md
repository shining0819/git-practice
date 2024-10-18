*06_git1 Lecture Note*

1. Version Control & Collaboration
   - It is essential to use a version control system for software development and other documentation works.
   - Basic solution: Making copies 
      - 프로젝트_최종.txt -> 프로젝트_최종_수정.txt...
        - Version Control: git makes this process easy!!
   - We need a systematic management system for version control and collaboration
    
2. Changes VS Snapshots
   - Changes: Storing data as changes to the base version
   - Snapshots: Storing data as snapshots
      - ex) Version 1 including File A, File B and File C, Snapshots store A1

3. Local, Centralized and Distributed Version Control
   - Centralized: Owned version Data Base from a central server
   - Distributed: Owned version Data Base from a each user
      - The server can be restored quickly, because each user store Version Data Base!!

4. Three states in Git(**Modified**, **Staged**, **Committed**)
   1. **Modified**: Working Directory
   2. **Staged**: Staging Area
   3. **Committed**: Get directory(Repository**)

5. Git config
   - **$ git init**: Initializing a repository in an existing directory
   - **$ git status**: Checking repository status
   - **$ git add [file_name]**: Adding a new file to be staged(tracked)
   - **$ git rm --cached [file_mame]**: Unstaging a file
   - **$ nano .gitignore**: Ignoring a file
   - **$ git commit -m "commit message"**: Commit
   - **$ git branch**: Change branch name
     
