# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from 
`https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo` (with an incredibly unstable internet connection 
in new mexico that proved to be quite challenging) .
### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
# Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
Complete this section with details from your setup:
- Repository URL: https://github.com/<USERNAME>/py4eda-work
- Output of `git remote -v`:
origin	https://github.com/abbeygodfrey/py4eda-work.git (fetch)
origin	https://github.com/abbeygodfrey/py4eda-work.git (push)
- The output of `git log --oneline`:
31bdd33 (HEAD -> main, origin/main) Add hw3a solution document
872e6e0 Initial commit: Add README and .gitignore
## Questions
### Reflections

**Question 1:**

a) I totally didn't use to have a separate file on my desktop for every version of my code... 
that would be stupid... 
All seriousness, when I was working on code by myself, I just made separate copies or would 
comment out my work but not delete it when doing multiple versions. But, I have used GitHub for 
group work before. One advantage to working in git through my terminal is its offline 
capability. I did most of this assignment on a plane. Another benefit to git is the branching 
aspect of repos, and also having a personal clone of the class repo that can be updated by a 
simple pull.

b) During Man 2 there's a case study that requires python, and I think I went through 7 or 8 
code iterations to get that thing to work, and I was jumping back and forth between versions 
trying to isolate what worked and what didn't. It would have made keeping track of everything 
so so much easier and I probably would've spent at least an hour less of my time on that 
assignment.

**Question 2:**

a) It's important to have separation as a fail safe, but also for organization purposes. First 
of all, we are learning, which means it's likely we'll make a mistake. For example, I tried to 
edit this homework file in class_repo because I wasn't paying attention to what directory I was 
in. We could make a mistake to the class repo that could be incredibely detrimental to all of 
us. Also, it's helpful to have your own work in a separate place to stay organized and build 
creation skills. 

b) I would create a separate repository for a group project, but maintain my individual work in 
one repository. I would create a separate repository for each class, and if I had general 
materials or practice problems, I would put them in a separate repository too.

**Question 3:**

a) The second is far more useful because it actually tells you what was changed between this 
version and the previous. If you updated the hw document and made an additional commit which 
ended up breaking your code, you might want to go back to this version and the comment will 
help you differentiate between updates.

b) I would likely make my commits corresponding to my work, and not a specific time frame. If I 
made any core or drastic changes, I would make a commit to help with version history. I 
wouldn't want my commits to be too big or span too long of a time frame, so I would likely get 
in the habit of committing my changes after I'm done working at every sitting, especially if it 
was a group project.

### Graduate Questions
**Question 1:**

a) The readme and gitignore files were to describe and set up the repo, not actual work, 
whereas the homework assignment was an actual file. These were smart to be kept separated 
because one is set up documents and one is something that you may possible need to roll back to 
earlier versions. 

b) I would commit the load data code, typo, and readme update (although I would commit readme 
separate from the other two). I would do these because the readme file is important for your 
repository, and the other data is completed and working. I would wait on the new analysis 
function because it's not completed, which I would leave in staging.   

c) Git status highlights modified files, shows changes, and reveals deleted or untracked files. 
This helps you break things into smaller chunks to be staged for commits. You should use it 
before starting work, after making changes, and before and after staging and committing 
changes.

**Question 2:**

a) My understanding of distributed version control is cloning repos versus collaborating 
directly. Essentially, the files are distributed individually and are elligible for unique 
changes made in separate repos, allowing for personal file control, as opposed to Google Drive 
or Dropbox, which is ongoing collaboration and rewriting.

b) I already mentioned that I appreciated the ability to work on this without an internet 
connection because it makes works a lot more flexible. I'm not dependent on the internet 
connection, and I also don't have to worry about accidently overwriting my repo because I would 
have to be very intentional to push my changes. 

c) Originally, you clone a repository, and then to update it as necessary, you can pull. 
However, you can't push to the class repository because we don't have the proper permissions, 
whereas with my_repo, you can use all three commands because it is a repository that we made 
and control.

**Question 3:**

a) It's important to recognize that you're not perfect, even in a professional world. There are 
mistakes that are worth being shown on public repositories because they show that you learned 
something, but there are other mistakes, like typo and simple code errors, that don't 
necessarily need to be made public because they don't add value to your work or show your 
learning process. 

b) When looking at a protfolio repository, you may have a lot of different things involved in 
it, that may require explanation. But also, this is a good place to specify where this work 
came from, why you did it, and credit any necessary people, whereas for an open-source project 
that is something people may want to use, the readme file may need to be more instructional 
base, although it would also make sense to contain credits.

c) Some habits that we should pay attention to now are simple things that show polish, like 
spacing and grammar, but also bigger things, like adhering to coding standards and best 
practices, that show that we are taking this course seriously, but also that we have created a 
good baseline that will be useful in the workplace. 
