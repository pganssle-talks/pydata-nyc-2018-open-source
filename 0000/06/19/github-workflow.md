# GitHub workflow

<style>
img#git-workflow {
    width: 70%;
}
</style>


<section data-transition="slide none">
    <img src="images/gh-workflow/ghw00-initial.svg" id="git-workflow"
         alt="Initial state - one repository on github" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw01-fork.svg" id="git-workflow"
         alt="Shows a second repository, the result of a GH fork" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw02-clone.svg" id="git-workflow"
         alt="The forked repository is cloned locally" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw03-upstream.svg" id="git-workflow"
         alt="The local repository is connected to the upstream with git remote add" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw04-names.svg" id="git-workflow"
         alt="Shows how each of the repositories is traditionally named: local, origin, upstream" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw05-locations.svg" id="git-workflow"
         alt="Demonstrates that origin and upstream are both on github's servers" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw06-branch.svg" id="git-workflow"
         alt="Shows a branch created on the local repo" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw07-branch-names.svg" id="git-workflow"
         alt="Shows the names of the branch: master, origin/master, upstream/master and fix-race-condition" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw08-push-names.svg" id="git-workflow"
         alt="fix-race-condition is pushed to origin, creating an origin/fix-race-condition branch" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw09-pr.svg" id="git-workflow"
         alt="A pull request is made from origin to upstream" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw10-pr-merged.svg" id="git-workflow"
         alt="The PR is merged, adding commits to upstream's master" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw11-pull.svg" id="git-workflow"
         alt="The local copy is updated by pulling from upstream" />
</section>

<section data-transition="slide none">
    <img src="images/gh-workflow/ghw12-delete.svg" id="git-workflow"
         alt="The feature branch is deleted in local" />
</section>

