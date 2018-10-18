# Using GitHub
<img src="images/make-pr/fork-repo.png"
     alt="Image showing the 'Fork' button in the top-right corner of the GitHub UI"
     id="ghscreenshot"
     />

<img src="images/make-pr/forked-repo.png"
     alt="Screenshot of the forked repo"
     id="ghscreenshot"
     /> <fragment/>

Note:

So now that we understand the abstraction, here's what it actually looks like to make a pull request on GitHub.

Not all projects use GitHub, but a lot of them do and the general concepts are similar between GitHub, BitBucket and GitLab at least.

--

## Clone the repo

<img src="images/make-pr/clone-repo.png"
     alt="Image showing the 'Fork' button in the top-right corner of the GitHub UI"
     id="ghscreenshot"
     />


```bash
$ git clone git@github.com:pganssle/pydata-nyc-2018-open-source.git
Cloning into 'pydata-nyc-2018-open-source'...
remote: Enumerating objects: 29, done.
remote: Counting objects: 100% (29/29), done.
remote: Compressing objects: 100% (18/18), done.
remote: Total 654 (delta 12), reused 21 (delta 8), pack-reused 625
Receiving objects: 100% (654/654), 38.65 MiB | 2.16 MiB/s, done.
Resolving deltas: 100% (190/190), done.
```

--

## Make a branch and push it to origin

```bash
$ git push --set-upstream origin add_pr_slide
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 174.51 KiB | 10.91 MiB/s, done.
Total 9 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote: 
remote: Create a pull request for 'add_pr_slide' on GitHub by visiting:
remote:      https://github.com/pganssle/pydata-nyc-2018-open-source/pull/new/add_pr_slide
remote: 
To github.com:pganssle/pydata-nyc-2018-open-source.git
 * [new branch]      add_pr_slide -> add_pr_slide
Branch 'add_pr_slide' set up to track remote branch 'add_pr_slide' from 'origin'.
```

--

<!-- .slide: data-transition="slide-in none-out" -->

## Create the pull request

<!-- Would prefer a better way to do this... -->
<style>
img.make_pr {
    position: absolute;
    width: 993px !important;
    height: 267px !important;
    top: 0 !important;
    left: 0 !important;
    max-width: 993px !important;
    max-height: 267px !important;
}
</style>

<div style="position:relative; width:1000px; height: 300px; margin:0 auto;">
    <img src="images/make-pr/make-pr.png"
         alt="Image showing the 'Compare & pull request'  dialog after a new branch is pushed"
         id="ghscreenshot"
         class="fragment fade-out make_pr"
         data-fragment-index="0"
         />

    <img src="images/make-pr/make-pr-box.png"
         alt="Showing how to make a PR when the dialog isn't there"
         id="ghscreenshot"
         class="fragment fade-in make_pr"
         data-fragment-index="0"
         />

</div>

<div style="position: relative; width: 99%; height: 500px">
    <img src="images/make-pr/create-pr-dialog.png"
         alt="Image showing what it looks like to create a pull request"
         id="ghscreenshot"
         />
</div> <fragment/>

--

<!-- .slide: data-transition="none-in none-out" -->
## Create the pull request

<img src="images/make-pr/make-pr-box.png"
     alt="Showing how to make a PR when the dialog isn't there"
     id="ghscreenshot"
     />

<div style="position: relative; width: 99%; height: 500px">
<img src="images/make-pr/pr-made.png"
     alt="Image showing a completed pull request"
     id="ghscreenshot"
     />
</div>

