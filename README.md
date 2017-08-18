# Assignment One

1.  Fork this repository into your own GitHub account.

2.  Clone that forked version to your local machine. Check that the
    `README.md` file looks like this file.

3.  Create a new branch to work in. Call it `add-my-details`.

        git checkout -b add-my-details

    (notice the `-b` flag. It's important. Why?)

4.  Edit the file `about.me`, replacing my name and ID with yours.

5.  Have a look at the differences between your working copy of the
    file and the one you started with:

        git diff

6.  Commit the changes to your local repository

        git add about.me
        git commit -m 'added my details'

7.  Go back to the master branch.

        git checkout master

8.  Have a look at `about.me`. Your changes are gone!

9.  Go back to the branch you did the work in

        git checkout add-my-details

10. Have a look at the file now. You should see the changes you made.

11. Push the file to your github account:

         git push -u origin add-my-details

    The first time you push from a branch, you have to tell git where
    to put it on the destination repository. `origin` is the default
    name for a repository you clone, so this is saying "store it back
    in the original remote repository in the `add-my-defaults` branch.

12. Visit your project on GitHub. Switch to the "add-my-details" branch
    and generate a pull request. Make sure to include your name and SMU ID
    in the notes.

