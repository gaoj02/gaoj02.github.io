---
permalink: /
title: "Zhen Song"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

The primary research focus involves employing methodologies from computer science, mathematics, physics, biophysics, and electrophysiology to develop computational simulation models of the cardiac system. Fine-grained multiscale mathematical models at physiological and biochemical levels serve as research tools to investigate fundamental physiological and pathological mechanisms related to the heart. Current research directions center on creating a multiscale cardiac electrophysiology virtual simulation platform through interdisciplinary technologies, as well as developing computer-aided systems based on experimental and clinical data for applications such as virtual surgical rehearsal, anti-arrhythmic drug development, and general drug cardiac toxicity assessment.

Educational Background
======
2006-2013 Northeastern University（Boston, MA, United States） | PhD in Physics   
2001-2005 University of Science and Technology of China  (Hefei, Anhui, China)  \| Bachelor of Science in Physics

Position
======
2020-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Associate Researcher， Peng Cheng Laboratory (Shenzhen, Guangdong, China)  
2018-2020&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Assistant Researcher,  University of California, Los Angeles (Los Angeles, California, United States) 


‌Peer-reviewed academic works
======
1. Wan, X., Cutler, M., **Song, Z**., Karma, A., Matsuda, T., Baba, A., Rosenbaum, D. (2012). New experimental evidence for mechanism of arrhythmogenic membrane potential alternans based on balance of electrogenic INCX/ICa currents Heart Rhythm 9(10), 1698 1705.(IF=5.225)
1. **Song, Z**., Ko, C., Nivala, M., Weiss, J., Qu, Z. (2015). Calcium-Voltage Coupling in the Genesis of Early and Delayed Afterdepolarizations in Cardiac Myocytes Biophysical Journal 108(8), 1908 1921. (IF=3.665)
1. Pezhouman, A., Singh, N., **Song, Z**., Nivala, M., Eskandari, A., Cao, H., Bapat, A., Ko, C., Nguyen, T., Qu, Z., Karagueuzian, H., Weiss, J. (2015). Molecular Basis of HypokalemiaInduced Ventricular Fibrillation Circulation 132(16), 1528-1537. (IF=23.054)
1. Chan, Y., Tsai, W., **Song, Z**., Ko, C., Qu, Z., Weiss, J., Lin, S., Chen, P., Jones, L., Chen, Z. (2015). Acute reversal of phospholamban inhibition facilitates the rhythmic whole-cell propagating calcium waves in isolated ventricular myocytes Journal of Molecular and Cellular Cardiology 80(C), 126 135. (IF=5.055)
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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
