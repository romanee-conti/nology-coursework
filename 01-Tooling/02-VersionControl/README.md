To initialise git on a local directory = git init
To clone/connect to an online repo = git clone <insert url here>
Or you can pull to your local machine = git remote add origin
To stage = git add -A
To make a commit = git commit -m "Insert note here".
To upload = git push origin main


Clone: Get a working copy of the remote repository.

Pull: I am working on this, please get me the new changes that may be updated by others.

On master/main branch naming default:
https://jarv.is/notes/github-rename-master/

When trying to delete a directory with rm -r and get the override r--r--r-- error, then must restore rights to directory using the following command:

chmod -R +w {file name}