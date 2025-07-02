---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**I am on the job market for full-time positions and open to opportunities in the industry.**

I completed my PhD at MIT where I worked with [Roy Welsch](https://mitmgmtfaculty.mit.edu/rwelsch/) (MIT Sloan), [Stan Finkelstein](https://hst.mit.edu/faculty-research/faculty/finkelstein-stan) (MIT and Harvard), [Zach Shahn](https://sph.cuny.edu/about/people/faculty/zach-shahn/) (CUNY), [Kenney Ng](https://research.ibm.com/people/kenney-ng) (IBM Research).

My research centers on the next generation of (generative) AI/ML for data-driven dynamic decision-making for real-world problems. Specifically, I focus on devising methods that explain the consequences of actions:

- Causal inference on multivariate stochastic processes using machine learning
- Foundation models/LLMs for causal inference
- Reinforcement learning with uncertainty quantification (e.g., conformal prediction or Bayesian active learning)
- Applications in finance, crypto, medicine, etc

**Machine Learning Research** experience:

I worked at [Scale AI, Inc](https://scale.com/) as a Generative AI Specialist and at [MIT-IBM Watson AI Lab](https://mitibmwatsonailab.mit.edu/) as a research assistant.

**Quantitative Research** experience:

I worked at [Point72 Asset Management](https://scale.com/) as a Quantitative Researcher and [Liberty Mutual Investments and the MIT Quest for Intelligence]([https://mitibmwatsonailab.mit.edu/](https://www.libertymutualgroup.com/about-lm/news/articles/liberty-mutual-insurance-establishes-artificial-intelligence-collaboration-mit)) as a research assistant.

Selected Publications
======
- [Can metformin prevent cancer relative to sulfonylureas? A target trial emulation accounting for competing risks and poor overlap via double/debiased machine learning estimators](https://doi.org/10.1093/aje/kwae217)
  by **S. Xu**, B. Zheng, B. Su, S. Finkelstein, R. Welsch, K. Ng, and Z. Shahn. American Journal of Epidemiology, 2025, 194(2), 512-523

- [Estimating heterogeneous treatment effects on survival outcomes using counterfactual censoring unbiased transformations](http://arxiv.org/abs/2401.11263)
  by **S. Xu**, R. Cobzaru, S. Finkelstein, R. Welsch, K. Ng, and Z. Shahn. Under revision at the Journal of the American Statistical Association (Theory and Methods)

- [Estimating cumulative treatment effects on target population by double/debiased machine learning](https://arxiv.org/abs/2305.02373)
  by **S. Xu**, S. Finkelstein, R. Welsch, K. Ng, I. Tzoulaki, and Z. Shahn. Submitted to the Journal of the Royal Statistical Society, Series B (Statistical Methodology)

- [Foundational model-aided automated high-throughput drug screening using self-controlled cohort study](https://openreview.net/forum?id=30EakJqzF0)
  by **S. Xu**, R. Cobzaru, S. Finkelstein, R. Welsch, and K. Ng. AI for New Drug Modalities (AIDrugX) at 38th NeurIPS, Vancouver, Canada, Dec 10-15, 2024

- [Systematically exploring repurposing effects of anti-hypertensives](https://onlinelibrary.wiley.com/doi/10.1002/pds.5491)
  by Z. Shahn, P. Spear, H. Lu, S. Jiang, S. Zhang, N. Deshmukh, **S. Xu**, K. Ng, R. Welsch, and S. Finkelstein. Pharmacoepidemiology and Drug Safety, 2022, 31(9), 944-952


<!--
My research focuses on natural language processing, stochastic process, and semiparametric theory.

blah
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:

- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

-->
