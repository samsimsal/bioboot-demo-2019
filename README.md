# bioboot-demo-2019
Live demo material for Biocomputing Bootcamp in 2019

1. Create README.md

# demo-github-2019
An example for students of Biocomputing bootcamp.

Please use this repo to inspect how GitHub presents commit history and their associated differences.

Note that this is a Markdown format text file. These are often used for documentation purposes as they allow easy text formatting and are rendered nicely by both GitHub and Bitbucket.

To learn more about markdown visit <https://help.github.com/en/articles/basic-writing-and-formatting-syntax>.

For this hands-on exercise please complete the five steps below: 

## 1. Exploring the [GitHub](https://github.com/hyunminkang/bioboot-demo-2019) repository.

- Clone this repo with `git clone https://github.com/hyunminkang/bioboot-demo-2019`
- Browse this repo on the website of [GitHub](https://github.com/hyunminkang/bioboot-demo-2019).
- Use your command line knowledge of git to inspect history, contributors and differences.

## 2. Creating your own GitHub account
Now create your own GitHub account at <https://github.com/> by using your UMICH email and a distinct passwd. Then create your fist GitHub repo by following these instructions:

- In the upper-right corner of any page, click **+** (plus symbol), and then click **New repository**.
- Create a name for your repository. For example, "demo-github-hyunminkang". (**note please replace hyunminkang with your unique name!**)
- Optionally, add a description of your repository. For example, "My first repository on GitHub."
- Choose a **public** repository. (Note that these are visible to any user on GitHub, so you can benefit from a collaborative community, but do please keep your content clean! 
- Select **Initialize this repository with a README**.
- Click Create repository.
- You can now edit your README.md file on GitHub or just clone to your machine with `git clone <URL>`

Congratulations! You've successfully created your first repository on GitHub, and initialized it with a _README_ file.

## 3. Syncing local and remote repos.

- On your machine cd to your new repo and add some content to the **README.md** file. Also create another file called **ToDo.md** with some items on your to-do list.
- Now add these to your local staging area with `git add README.md ToDo.md`
- Commit these to your local repo (i.e. still on your machine only) with `git commit -m "Edit README.md and add ToDo.md"
- Push these to your **remote** GitHub repo with 'git push -u origin master'

Congratulations! you have just updated your GitHub repo.

## 4. Collaborating with remote repos.

- Now partner with the person beside you and decide on **ONE repo** that you would like to collaborate on (i.e. the person on the right).

#### If you are owner of this **One repo**
- Add the other person as a collaborator to your GitHub repo.
- Ask for the **username** of the person you're adding as a collaborator. 
- On GitHub, navigate to the main page of the repository.
- In the repository's right sidebar, click  **Settings** (it looks like a little gear icon)
- Click the "**Collaborators**" tab.
- Start typing the collaborator's username.
- Select the user from the drop-down menu.
- Click **Add**.

#### If you are the collaborator to this repo
- Clone your partners repo by getting the URL from your partners GitHub page (`git clone <URL>`).
- Modify some of the files (for example add some content to the **ToDo.md** file)
- Go through the regular git add/git commit cycle.
- Push these changes to GitHub with `git push -u origin master`

Congratulations! you have now contributed to a shared collaborative repo! 

## 5. Fixing conflicts

- Now together with your partner pick a common line and edit it in different ways so you will have two distinct versions.
- First `git pull origin master` to sync with remote repo.
- Then `add/commit/push` your changes to GitHub.
- What happened?

Can you fix your first **conflict**?
