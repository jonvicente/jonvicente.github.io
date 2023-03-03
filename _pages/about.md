---
permalink: /
title: "Hey, I'm Jonathan Vicente"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




Bachelor of Science (BSc) in Biomedicine (BMedSci) [Anhembi Morumbi University - UAM](http://https://en.wikipedia.org/wiki/Anhembi_Morumbi_University) (2014 - 2017) with a degree in Clinical Pathology, also certificate in Political Science with a research thesis ***"O processo político de criação do SUS com base na Lei 8080/90"*** at [USCS - Municipal University of São Caetano do Sul](https://en.wikipedia.org/wiki/Municipal_University_of_S%C3%A3o_Caetano_do_Sul) (2019). Master of Science (MSc) in [Public Health | Collective Health](https://sites.usp.br/saudecoletivafmusp/) with a research thesis ***"The Influence of COVID-19 on Mental Health of Healthcare Workers in the Hospital and Intensive Care Unit: Scoping Review"*** at the Department of Preventive Medicine of the Faculty of Medicine of the [University of São Paulo - USP](https://en.wikipedia.org/wiki/University_of_S%C3%A3o_Paulo) (2020 - 2022) and associate of the [Yale-Proxima](https://www.iniciativa-proxima.org/) Associates Class'21.

![Illustration of combining vision and language modalities](/images/capa_2.png){:.align-center width="700px"}

**RESEARCH**: [Social](https://en.wikipedia.org/wiki/Social_science) and [Human Sciences](https://en.wikipedia.org/wiki/Human_science) in [Public Health](https://en.wikipedia.org/wiki/Public_health), [Psychiatric Epidemiology](https://en.wikipedia.org/wiki/Psychiatric_epidemiology), [Mental Health](https://en.wikipedia.org/wiki/Mental_health), [Health Policy](https://en.wikipedia.org/wiki/Health_policy), [Preventive Medicine](https://en.wikipedia.org/wiki/Preventive_healthcare) and [Reviews](https://en.wikipedia.org/wiki/Systematic_review). Member of [***Ayé Nucleus***](https://www.instagram.com/nucleoaye/), the [***Brazilian League of Black Science***](https://www.instagram.com/lcpbrasileira/) and the Study and Research Group on [***Health, Intersectionality and Social Markers of Difference***](https://sites.usp.br/simas/)(SIMAS) at FMUSP. He is a member of the working group for Affirmative Policies of the *Graduate Programme in Collective Health* of the Department of Preventive Medicine of the USP School of Medicine and is also a student representative (leader) on the [**FMUSP - Graduate Committee**](https://www.fm.usp.br/posgrad/portal/comissao-de-pos-graduacao) (2021 - 2022). He supervised the [UC4: Process Health-Disease-Care I](https://uspdigital.usp.br/jupiterweb/obterDisciplina?nomdis=&sgldis=MSP1041) (MSP1041-MSP1042-MSP1043) of the Faculty of Medicine of FMUSP.

Science Communication
======

Most of the time, researchers aim to communicate the results of their work to other researchers. Sometimes, however, they feel the need to get their science across to a larger audience. Here is a collection of articles to help scientists communicate science effectively to the public and policymakers.

<a class="twitter-timeline" data-height="500" data-theme="light" href="https://twitter.com/jonathanvicent?ref_src=twsrc%5Etfw">Tweets by jonathanvicent</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
