# Welcome
These materials have been developed by a Covid-19 community support group in consultation with the Fairfax County Health Department.

Click [Downloads](index.html) to get started 

# Resources

[Downloads](index.html)

[About](index.html)

[Acknowledgements](index.html)

[Contact](index.html)


        {% if site.show_downloads %}
        <ul class="downloads">
          <li><a href="{{ site.github.zip_url }}">Download <strong>ZIP File</strong></a></li>
          <li><a href="{{ site.github.tar_url }}">Download <strong>TAR Ball</strong></a></li>
          <li><a href="{{ site.github.repository_url }}">View on<strong>GitHub</strong></a></li>
        </ul>
        {% endif %}


        {% if site.github.is_project_page %}
        <p>This project is maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></p>
        {% endif %}
        <p><small>Hosted on GitHub Pages &mdash; Theme by <a href="https://github.com/orderedlist">orderedlist</a></small></p>
