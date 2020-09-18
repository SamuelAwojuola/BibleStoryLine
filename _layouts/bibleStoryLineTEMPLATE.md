{% include BStL-head.html %}
{% include BStL-header.html %}
{% include BStL-customAlert.html %}
{% include BStL-controlsSection.html %}
{% include BStL-masterTable.html %}

<!--the content is the dynamic part of the page which are
1. the storyLineTable itself
2. the details section
-->
{{content}}
<!--**********************************************-->

{% include BStL-storylineEditorSection.html %}
{% include BStL-foot.html %}