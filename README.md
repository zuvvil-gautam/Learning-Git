
# Learning-Git
<h3>GIT BASICS</h3>
<ul>
    <li><b>git init</b> - This creates an empty git repository in current directory. </li>
    <li><b>git add {directory} </b> - Stage all the changes, for the next commit. Replace the {directory} with the
            file you want to stage.(git add index.html)</li>
    <li><b> git commit -m "message"</b> - Commit the staged snapshot with the desired message.(git commit -m "create html file") </li>
    <li> <b>git status</b> - the list which shows all the files which are staged , unstaged and untracked.</li>
    <li><b>git log </b>-It displays the entire commit history.</li>
    <li><b>git diff</b>- It shows unstaged changes between your index and working directory.</li>
</ul>

<h3>GIT BRANCHES</h3>
<ul>
    <li><b>git branch</b>Shows list of all the branches in your repository.</li>
    <li><b>git checkout -b {branch} </b>-it first checks if there's an existing branch, if not it creates a new one.
        (note: -b is necessary,if there's no existing branch then it throws error.) </li>
    <li><b>git merge {branch}- </b>Merge <branch> into specific branch.</li>
</ul>

<h3>REMOTE REPOSITORIES</h3>
<ul>
    <li><b>git remote add <name>
                {url} </b>-it creates a new connection to a remote repository like in Github. After adding a remote,you
        can use {name} as a shortcut for {url} in other commands.</li>
    <li><b>git pull {remote}</b>- It fetches the specified remote's copy of current branch and immediately merge it into
        the local copy.</li>
<li><b>git push {remote}{branch}- </b>Push the branch to {remote}, along with the necessary commits and objects. Creates named
            branch in the remote repository if it doesn't exist.</li>
</ul>

<h3>GIT CONFIG</h3>
<ul>
    <li><b>git config --global user.name {name} -</b> Define the author name to be used for all commits by the current
        user.</li>
    <li><b>git config --global user.email {email} -</b> Define the author email to be used for all commits by the
        current user.</li>

</ul>


