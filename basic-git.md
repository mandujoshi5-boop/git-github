GitHub Notes:-

Git:-helps to track changes in code(VCS).

Git Configuration:-
✅git config --global user.name"Name of the User"
✅git config --global user.email"User email Id"
✅git config --list(// it will show the detail of who is loggin the git commit or the user info.)
Clone&Status--
Clone--cloning a repository on our local machine(syntax[✅git clone <-https link from the GitHub account->])(mostly used in the HTTPS)
Status--display the status of the code[✅git status]

There are mostly two types of streams--
local--the local means the file which you are working on the laptop.
remote--the remote means the file you directly commit on the GitHub or contribute.

CD(changed directly)--
it's is used to move from the external files to the internal files that will always procced the operation on internal file
CD..
it is used to exit from the working repo(it is used to move from interal to the external).

Clone--it's used to copy your project from your GitHub repo to the code editor.
Status--it's an add to the commit process.
        Can see changes through status commend.

type of Status--
untracked--new files (which we are created) not tracked by git.
modified--changed one(indicated my M)( sign after file name)
unmodified--unchanged one(indicated by U)(,,)
staged-- there are three stages

|Make new changes(added file or something)|-->|✅add(this stage id known as staged)|-->|File is ready to commit|.

ADD&COMMIT--
Add--changed files in working directory to the Git area([✅ git add <-File name->])
commit--the record of change([✅ git commit -m" the changed thing "])

PUSH command--
it upload your work from local repo content to the remote level( from code editor-->GitHub)
([✅ git push origin main])

[✅ git init ]--
it is used to create the empty repo in the local server rather than in remote one

after creating the new fime on the local level on the code editor, One should create a new repo on the remote level on the GitHub
after creating the new file on the GitHub gut copy link and

Init Command--
✅ git init
✅ git remote add origin #link-->(add your new GitHub repo link here)
✅ git remote-v      (to verify remote)-->it is used just to verify it actually connect to your GitHub repo
✅ git branch        (to check branch)-->tell us about
✅ git branch-M main (to rename branch)
✅ git push origin main
