

Looking for help on git, check out the documentation.

https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control



See a neat repo you'd like to contribute to, "clone" it.
I have a directory in my home called "gits" where I clone all my repos.

```
cd ~/gits
git clone git@github.com:everhartlab/APS_IntroR_2019.git
```


Want to add updates from a remote to your local version.


```
git pull origin master
```


Want to create a new branch that you can work on.

```
git branch bjk
```

Creates a new brnch called "bjk" (my initials, but you can make up your own name).

Wait, are there any existing branches?
List them.

```
git branch
```

Want to work on that new branch you created, check it out.

```
git checkout bjk
```

Now you can work on that branch.
Once you've made some changes, you'll want to commit them.

```
git commit -m "Made some changes that you're going to describe better than I have in this example"
```


And now you'll probably want to "push" these changes to a remote (e.g., GitHub).

```
git push origin bjk
```

Don't forget to pull before you push because if changes were made to the remote it will generate a conflict you'll have to resolve.

