---
permalink: /
title: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Welcome!

I am a third-year Computer Science PhD student at the [University of California, Irvine](https://uci.edu/). My research interests are:

1. **Designing Algorithms under Uncertainty**  
   I develop robust algorithms capable of handling uncertain inputs and dynamic environments. My work in this area covers topics such as online algorithms and algorithmic game theory.

2. **Decentralized Data Markets**  
   I investigate new models for data exchange and federated learning, contributing to the emerging field of decentralized data markets.

## Academic Background

Before joining UCI, I earned my **M.Sc. in the D-MTEC Department** at [ETH Zurich](https://ethz.ch/), under the guidance of [Prof. Hans Gersbach](http://www.gersbach.de) and [Dr. Akaki Mamageishvili](http://mamageishvili.info). My master’s thesis examined liquid democracy and the impact of free vote delegation in proof-of-stake blockchains.

I completed my **B.Sc. in Electrical Engineering** (with a minor in Computer Science) at [Sharif University of Technology](http://www.sharif.edu/), where I worked on machine learning applications in medicine under the supervision of [Prof. Babak Khalaj](https://sharif.edu/~khalaj/).

Additionally, I have enriched my academic journey through research assistant roles at the **KOF Swiss Economic Institute** and the **KTH Royal Institute of Technology** in Sweden. In the summer of 2024, I had the privilege of visiting [UIUC](https://illinois.edu/) to collaborate with [Prof. Ruta Mehta](https://rutamehta.cs.illinois.edu), [Prof. Jugal Garg](https://jugal.ise.illinois.edu), and [Prof. Bhaskar Ray Chaudhury](https://www.bhaskar-ray-chaudhury.com) on several exciting projects.

---

Feel free to explore my website to learn more about my research and academic journey.

<!-- Welcome! I am a third-year Computer Science PhD student at University of California, Irvine. My main research interests broadly fall into the following two categories:
1- Designing algorithms under uncertainty, where the goal is to design algorithms for uncertain inputs or environments. For example areas such as Online Algorithms, and Algorithmic Game Theory. 

2- Decentralized data markets: topics on data markets, exchange and federated learning. 

Before coming to UCI, I got my M.Sc. in the D-MTEC department at ETH Zurich, where I was advised by Prof. Hans Gersbach and Dr. Akaki Mamageishvili. My master's thesis was about liquid democracy and studying the effect of free vote delegation in proof-of-stake blockchains. I received my B.Sc. degree in Electrical Engineering and a minor degree in Computer Science from Sharif University of Technology. There I worked on machine learning in medicine design under the supervision of Prof. Babak Khalaj. I have also worked as a research assistant at KOF Swiss Economic Institute and KTH Royal Institute of Technology in Sweden. In summer 2024, I visited Prof. Ruta Mehta at UIUC, where I had the privilage of working with many new interesting projects.  -->


<!-- 
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
