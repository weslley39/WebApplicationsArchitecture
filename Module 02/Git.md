##Distributed Version Control with Git

Git is a popular open source distributed version control system created in 2005
by the Linux development community.

Provides means for comparing the differences between different versions
of the project.

Git track files, and they reside in three "locations".

**Stages of files in working directory:**
- Tracked, the files that were saved to the git when you perform a commit
- Untracked, all other files

**Tracked files can be:**
- Modified
- Unmodified
- Staged

commit -a -------------------------->| push <remote> <branch> --------------->|
add . -------------->|commit ------->| push <remote> <branch> --------------->|
[Working Directory]  (Staging Area)  [Local Git Repository] [Remote Repository]
|<--------------------------------------checkout <branch> |<--------------fetch
|<----------------------------------------merge<branch>   |<--------------fetch
|<----------------------------------------------------------------clone<remote>
                                                                       or
                                                                  pull <remote>