##### Web Track
[Back to Class 6](../../class6)

# Studio: FlickList 5



### Demo

Here is a demo of what you are trying to accomplish: <a href="http://htmlpreview.github.io/?https://github.com/LaunchCodeEducation/flicklist/blob/636afdd8442225455cef24ea4a8560705a17313c/index.html" target="_blank">FlickList 5 Demo</a> (note: I noticed some weird behavior with this demo on Safari, so be sure to open it up in Chrome). Play around with the demo for a minute and get familiar with its features. Also, keep the demo open in a separate window, so you can refer to it while working on the assignment.

Note the following additions since last time:
* The proverbial furniture has been rearranged. The two sections (watchlist and browse) are no longer arranged in side-by-side columns; instead the browse section has moved back to its former home, below the watchlist section.
* The browse section is way different. Rather than displaying all the movies at once inside a list, now only one movie is shown at a time. The user can cycle through movies using a fancy UI "carousel", which displays the movie posters along with buttons for sliding back and forth between movies. Each time the carousel slides, the movie title and description update to reflect the newly active movie whose poster has slid into view. 
* The browse section layout uses the Bootstrap grid system, in fact a *nested* grid: At the macro level, the section is split into (A) a column on the left for the movie info and carousel, and (B) a column on the right for the search form. Diving into that first column, it is further subdivided into (A-1) a column on the left for the movie title and overview, and (A-2) a column on the right for the carousel and the "Add to Watchlist" button.


### Starter Code

Same procedure as usual. First, fetch the studio4 branch from upstream:

```nohighlight
$ git fetch upstream studio4
remote: Counting objects: 21, done.
remote: Compressing objects: 100% (15/15), done.
remote: Total 21 (delta 6), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (21/21), done.
From https://github.com/LaunchCodeEducation/flicklist
 * branch            studio4    -> FETCH_HEAD
   74b1223..fe10c4f  studio4    -> upstream/studio4
```

Then, checkout a new local branch:

```nohighlight
$ git checkout -b studio4-my-work upstream/studio4
Branch studio4-my-work set up to track remote branch studio4 from upstream.
Switched to a new branch 'studio4-my-work'
```

### A Brief Tour


##### index.html

##### flicklist.js

##### styles.css

### Assignment

Work your way through the TODOs in the source code. The tasks are numbered. You should work on them in the order prescribed, as follows:

##### 0. API key


##### 1. Rearrange to use grid

##### 2. Put in Carousel and Browse Info

##### 3. Add carousel buttons

##### 4. bind

##### 5. CSS

##### 6. 

##### 7. 

##### 8. 

##### 9. 

### How to Submit

As usual, commit your work on Git and push to a new branch on your GitHub repo. Then, submit a link to your repo on Vocareum.

##### Commit and Push

If you run the `git status` command, you should see that you now have *unstaged* changes:

```nohighlight
$ git status
On branch studio4-my-work
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
      
        modified:   css/styes.css
        modified:   index.html
        modified:   js/flicklist.js

no changes added to commit (use "git add" and/or "git commit -a")
```

We can stage these changes with the `add` command:

```nohighlight
$ git add --all
```

The `--all` adds all of the unstaged files, so you don't have to type them one by one.

If you check your status again now, you should see:

```nohighlight
$ git status
On branch studio4-my-work
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
        modified:   css/styes.css
        modified:   index.html
        modified:   js/flicklist.js
```

All the files are now staged for committing. Go ahead and make a commit, using the -m flag to remind your future self (and others looking at your code) what changes you made during this commit:

```nohighlight
$ git commit -m "finish FlickList 4 studio"
[studio2-my-work 46db232] finish FlickList 4 studio
 2 files changed, 2 insertions(+), 2 deletions(-)
```

The convention is to write your commit messages using the present tense rather than past tense (e.g. "finish" rather than "finished").

If you check your status one more time, you should see this:

```nohighlight
$ git status
On branch studio4-my-work
nothing to commit, working directory clean
```

Finally, *push* your changes to your remote repo:

```nohighlight
$ git push origin studio4-my-work
Counting objects: 62, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (20/20), done.
Writing objects: 100% (22/22), 2.36 KiB | 0 bytes/s, done.
Total 22 (delta 6), reused 0 (delta 0)
To https://github.com/jharvard/flicklist.git
 * [new branch]      studio4-my-work -> studio4-my-work
```

If you go back and revisit github.com/jharvard/flicklist, you should now see your new branch up there! Specificially, near the top-left of the screen, you should see a dropdown menu that says "Branch: master". Click that dropdown and you should see an option for "studio2-my-work". Click on that branch, and you should now see the code you just worked on. Copy the current url in your browser's address bar (you are about to paste that url into Vocareum).

##### Submit on Vocareum

On Vocareum, click the assignment titled **Studio: FlickList 4**. In your `/work` directory you should see a file called `studio4.txt`. Open up this file and fill in the link to your work on GitHub.


#### Publish your Work using Github Pages!
