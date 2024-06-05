git branch <br>
shows which branch you're on<br>
git branch name<br>
creates new branch called name<br>
git checkout name<br>
changes you the the branch called "name"<br>
git push <br>
will not work as there is and upstream error <br>
you will get a message that looks like this <br>
fatal: The current branch development has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin development

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.<br>
to resolve this<br>
git push --set-upstream origin development<br>
git add .
git -m "branch add, branch push" <br>
