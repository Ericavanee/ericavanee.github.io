---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I’m Erica 🙂, currently a Ph.D. candidate in Operations Research within the Department of Management Science & Engineering (MS&E) at [Stanford University](https://www.stanford.edu/). I am fortunate to be co-advised by Prof. [Jose Blanchet](https://web.stanford.edu/~jblanche/) (MS&E) and Prof. [Mert Pilanci](https://stanford.edu/~pilanci/) (Electrical Engineering). I am also grateful to be supported by the [Stanford Graduate Fellowship (SGF) in Science and Engineering](https://vpge.stanford.edu/fellowships-funding/sgf), generously sponsored by the [Koret Foundation](https://koret.org/grantees/cross-disciplinary-research-stanford-university/).

As part of my Ph.D., I recently completed a co-enrolled M.S. degree in Electrical Engineering (2025), specializing in Control & Optimization. Prior to Stanford, I earned a dual B.A. in Mathematics and Statistics from [Columbia College, Columbia University](https://www.college.columbia.edu/), graduating *summa cum laude* with honors from both departments.

This summer, I’m excited to be interning as an Applied Scientist working on Generative AI with [Amazon Science](https://www.amazon.science/) in the Bellevue office.

Research
======
My research lies at the intersection of optimization, statistics, and machine learning. As a theorist and statistician, I am particularly interested in revisiting and repurposing classical techniques from probability and optimization theory to tackle modern learning challenges, with a focus on improving sample efficiency in large-scale, high-dimensional settings.

Recently, my work has focused on the principled integration of large language models (LLMs) into traditional learning pipelines, leveraging their capacity to augment traditional statistics-driven learning pipelines with rich contextual metadata, while preserving tunability, robustness, and statistical rigor.

I have broad interests across learning, AI, and theoretical statistics & probability. Philosophically, I’m inspired by mathematician [Hans Hahn's](https://en.wikipedia.org/wiki/Hans_Hahn_(mathematician)) view of mathematics as a precise, elegantly constructed conceptual framework: one that enables us to abstract information and perform tautological transformations to uncover fundamental laws governing our world. As I continue journey as a researcher, I aim to uncover more of these hidden structures within learning systems through the lenses of optimization and statistical theory and push the frontiers of what we can rigorously understand and design in machine learning.

Feel free to reach out if you're interested in my work!

Publications and Working Papers
======
* *Active Learning of Deep Neural Networks via Gradient-Free Cutting Planes*  
  **<u>Erica Zhang</u>**<sup>*</sup>, Fangzhao Zhang<sup>*</sup>, Mert Pilanci  
  *International Conference on Machine Learning (ICML), 2025*  
  <sup>*</sup>Equal contribution  
  [PDF](https://example.com/paper.pdf) [arXiv](https://arxiv.org/abs/XXXX.XXXXX)


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
