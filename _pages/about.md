---
permalink: /
title: "Hi there!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a second-year PhD candidate in <b>artificial intelligence (AI)</b> at the Intensive Care department, Erasmus Medical Center, Rotterdam, the Netherlands. 
Our lab, the [Datahub](https://datahub.health/), works towards data-driven decision support in the intensive care unit. Supervised by Diederik Gommers, Jasper van Bommel and Michel van Genderen, our studies vary from live-dashboarding for health quality monitoring to prediction modeling and complex <b>'actionable AI'</b> through <b>Causal Inference</b>. We work together with the Pattern Recognition and Bioinformatics laboratory (Computer Science department Delft University of Technology), where I am supervised by Jesse Krijthe and Marcel Reinders. 

I finished my BSc ([Clincal Technology](https://www.tudelft.nl/onderwijs/opleidingen/bachelors/kt/bsc-klinische-technologie)) and MSc ([Biomedical Engineering](https://www.tudelft.nl/onderwijs/opleidingen/masters/biomedical-engineering/msc-biomedical-engineering)) at Delft University of Technology.




<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

Preprint on MedrXiv!
======
Recently, we have been systematically reviewing Causal Inference research in the ICU, discuss quality of these studies and give recommendations for future work towards 'actionable' AI in the ICU. Check out the preprint [here](https://www.medrxiv.org/content/10.1101/2022.10.29.22281684v1)!

New paper out! Dynamic model updating for Early Warning in COVID-19 patients.
======
We present an early warning model specifically for COVID-19 patients, showing a better predictive performance compared to traditional Early Warning Scores, ie the National early warning score aka [NEWS](https://pubmed.ncbi.nlm.nih.gov/23295778/) and the Modified early warning score aka [MEWS](https://pubmed.ncbi.nlm.nih.gov/11588210/).

<b>Dynamic model updating</b>: We performed a temporal validation by splitting all included patients into groups admitted before and after August 1, 2020. We simulated the situation in which the model would have been developed after the first and implemented during the second COVID-19 ‘wave’ in the Netherlands. We experimented with different model updating strategies, combining model refitting and hospital specific re-calibration (figure). 

<br/><img src='/images/model_updating.jpg' width="700" height="500">

Read all about it in our [paper](https://pubmed.ncbi.nlm.nih.gov/35958674/) published in [ICMx](https://icm-experimental.springeropen.com/)!


Dynamic mortality prediction in the ICU
======
Traditional risk scores like [APACHE IV](https://pubmed.ncbi.nlm.nih.gov/16540951/) provide mortality risk stratification for ICU patients upon admission. Our new study presents a model for dynamic risk stratification throughout the whole ICU stay, validated in the [Dutch Data Warehouse](https://ccforum.biomedcentral.com/articles/10.1186/s13054-021-03733-z) dataset, with more than 3000 COVID-19 patients admitted to 25 different ICUs in the Netherlands.

Check out our [paper](https://pubmed.ncbi.nlm.nih.gov/35958674/) in the special edition of Intelligence-Based Critical Care and Anesthesia!

<br/><img src='/images/Dyn_mort_results.jpg'>

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

<br/><img src='/images/500x300.png'>

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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
