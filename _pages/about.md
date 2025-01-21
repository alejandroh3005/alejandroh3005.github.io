---
permalink: /
title: "welcome! let me show you who I am & what I do ~"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

In short, I am a biostatistician with excellent people skills and a background in software engineering. I have expertise with data visualization, statistical modeling, project management, public speaking, and software documentation in collaborative settings. My passion is the application of statistics in public health to drive evidence-based decisions and contribute to improved healthcare outcomes.

🌱 where I come from:
======

Halfway through my undergraduate Computer Science degree, I had grown distant from the algorithms and architecture. I liked programming and recognized CS applications were important, but imagining a future as a software engineer felt like a poor fit. I wanted to lean into Data Science and peek behind the curtain of machine learning, so I began a Statistics minor. Those early semesters were very humbling, but class kept me engaged and peers motivated me as I grew a sense of belonging in their classrooms. The small Mathematics and Statistics department welcomed me into their community and the relationships I began in that period became very formative, especially that with Dr. Jimmy Risk. I was learning all the clever ways people bridge theory and application, what is lost and gained along the way, and how to bring meaningful insights into decision-making that impacts people's lives. I felt I had found my place in applied statistics and had been shown there was so much more. Toward graduation, someone suggested applying to a Biostatistics graduate program. After Googling "Biostatistics" and seeking reassurance from my professors, I decided to give it a shot!

🌳 where I am:
======

Graduate school has not just been an opportunity to gain technical skill, but to deepen my understanding of myself and my place in the world. I feel incredibly grateful to study in this renowned program, be exposed to brilliant public health work, and see directly where I contribute to it. It has been so rewarding to master what I consider to be the most challenging part of this field: making something useful when it is on some level wrong. I have totally transformed as a student and as a person since completing my undergraduate degree, bright and green.


🌟 where I'm going:
======

My future plans are to work! Since I started this program, I have become very familiar with what I am capable of. My passion is the application of statistics in public health to drive evidence-based decisions and contribute to improved healthcare outcomes. I look forward to entering the industry—applied statistics is fabulous work! I love to see new problems and learn lots of science, and I love to help people. Thoughtful, honest science has been my goal from the beginning and this experience has been an integral part of that achievement.  

A data-driven personal website
======

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
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


Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

