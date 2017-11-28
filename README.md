## Resources for openSAP course 3DMV - "Maps and 3D made easy with SAPUI5"

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### 3D Models

3D Models consumed by the examples can also be downloaded from this site.

{% loop_directory directory:Models iterator:file filter:*.vds sort:descending %}
   <a href="{{ image }}" text="{{ image }}"/>
{% endloop_directory %}

