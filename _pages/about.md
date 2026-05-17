---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am a Ph.D. Candidate in [Political Science at the University of Southern California](https://dornsife.usc.edu/poir/profile/claudia-salas-gimenez/), with an emphasis on International Political Economy and Political Methodology. I am also a Graduate Research Assistant at [The Security and Political Economy Lab](https://www.uscspec.org/).

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting


Research
======

Working Papers
------

[Who Influences Whom? Analyzing the Interplay of Mainstream and Outsider Parties in Social Media Campaigns](https://gonzalez-rostani.com/img/Papers/YouTube.pdf) (with Valentina Gonzalez-Rostani).

Social Ties and Diaspora Managers: Evidence from a Multi-Country Survey (with Junbeom Bahk, Benjamin A.T. Graham, and Sooyeon Kim).

Work in Progress
------
  
Automation, Risk, and Public Legitimacy (with Valentina Gonzalez-Rostani).


Teaching
======

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

------

## Talks

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
