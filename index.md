---
title: Home
---
# Sociology library sessions

Jekyll repository for "Sociology library sessions" at the University of Idaho Library.

<link to repository>

This website will teach you how to:
- find and utilize discipline-specific, peer-reviewed sources related to your research topic
- create and modify your search strategies
- use citation chaining backwards and forwards through a research topic

You can also download a Synthesis Matrix template as an <a href="{{ '/images/SynthesisMatrix_Template.xlsx' | relative_url }}">Excel</a> or <a href="{{ '/images/SynthesisMatrix_Template.csv' | relative_url }}">CSV</a> file.

<a href="https://vivo.nkn.uidaho.edu/vivo/display/n104190" target="_blank">**Questions about this website or its content?** 

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> hosted by the <a href="https://www.lib.uidaho.edu/" target="_blank">University of Idaho Library</a> ({{ site.pub_year }})
>
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}}. (get [source code]({{ site.repo }}))
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
