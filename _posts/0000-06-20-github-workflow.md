# GitHub workflow

<style>
img#git-workflow {
    width: 70%;
}
</style>

{% for image in site.data.gh_workflow.images %}
<section data-transition="slide none">
    <img src="images/gh-workflow/{{ image.name }}" id="git-workflow"
         alt="{{ image.alt }}" />
</section>
{% endfor %}
