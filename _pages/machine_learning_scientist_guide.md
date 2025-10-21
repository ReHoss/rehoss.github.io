---
permalink: /guide_ml_research/
title: "Advice and Resources for Machine Learning Researchers"
author_profile: true
---

Below is a collection of methods and tools to make your life as a machine learning scientist easier and more productive.
They have been gathered from many sources collected over time (blog posts, articles, personal experience, discussions with colleagues, etc.).


## 🧠 Mindset
- Always be open to new knowledge (see P. Kidger's detailed [blog post](https://kidger.site/thoughts/just-know-stuff/))
- Make contacts and don't be shy to interact with anyone
- Critical thinking and humility

<br>

## 🔬 Research
### Approach
- **During investigations, <span style="color:red;">reduce</span> as much <span style="color:red;">uncertainty</span> as possible to extract clear signals**.
 
- **Read paper reviews**.
This is useful to understand what the community expects from a good paper.
This highlights weaknesses of contributions that can be addressed in future/new works.

- **Pay attention to [HARKing](https://en.wikipedia.org/wiki/HARKing)** (Hypothesizing After the Results are Known).
This is a common pitfall in research that can lead to misleading conclusions. (It happened to me!)
A nice [paper](https://arxiv.org/abs/1904.07633) on the topic in Deep Learning.
 
- **Read papers entirely** this makes you feel you are doing proper research, meticulous and thorough.

- **Know reviewers instructions** and criteria for conferences/journals you are submitting to. This helps you understand what is expected from your work. ICML reviewer guidelines [here](https://icml.cc/Conferences/2025/ReviewerInstructions).

- **Review papers for journals or conferences**

### Bibliography
- Store your bibliography files and construct your **OWN** library
- Use Zotero or similar tools (Google Drive) to construct this library
- I personally use Google Drive synchronised on [PDF Expert](https://pdfexpert.com/) which allows to annotate documents with automatic synchronisation.
The latter tool greatly simplifies scanning and attaching handwritten notes to articles or books.


### Writing
- Microsoft Research (S. P. Jones) [presentation](https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper/) on how to write a great paper.
- Ask your local academic writing center for help.
- Write *before* using AI tools.

#### Softwares
- Latex
- Typst (promising tool)


### Talks, presentations and posters
- One minute by slide rule.
  Target a duration of 90% of the total time for your talk.
  This leaves time for unexpected events.
- Don't try to put the same level of details in a talk as in a paper.
  Try to be clear and transmit the essential ideas.
- If you are an intern, consider yourself as a researcher and play this role in your presentations.


#### Software for presentations
- [Beamer](https://www.overleaf.com/learn/latex/Beamer)
- Keynote (Apple)
- Google Slides
- Microsoft PowerPoint

#### Software for posters
- [Typst](https://typst.app/) (Recommended)
- [Beamer](https://www.overleaf.com/learn/latex/Beamer)
- [Inkscape](https://inkscape.org/)


### Communicating your research and building your profile
- Social Media & Blogs
- Conferences & Workshops
- Create a personal website


### Online social media about AI/ML
_Your presence on social media can help you stay updated with the latest research, demonstrate your expertise and interests, connect with other researchers, and share your own work._
Here are some popular platforms:
- Discord
- Hugging Face
- Reddit
- Stackoverflow
- X
- YouTube

### Blog articles
Personal blogs and articles are always a great source of inspiration and knowledge.
Some notable mentions are:

- P. Kidger [blog](https://kidger.site/thoughts/) and in particular his advice on [how to achieve success in ML research](https://kidger.site/thoughts/just-know-stuff/).
- J. Schulman [blog](http://joschu.net/blog.html).
- Lilian Weng [blog](https://lilianweng.github.io/).
- Terrence Tao [blog](https://terrytao.wordpress.com/).

<br>

## 🧑‍💻 Programming practices and software tools

Read the official tutorial for any tools (from Vim, VSCode, Git to Pytorch or Docker).
Those presentations are often advanced resources which contain important terminology.


### Python
_Following those principles eliminate lots of bugs and thus reduces **uncertainties** regarding your results._

- [Offical Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- [PEP 8](https://peps.python.org/pep-0008/)
- [Google Style Guide](https://google.github.io/styleguide/pyguide.html)
- [Python packaging](https://packaging.python.org/en/latest/tutorials/installing-packages/)
- Ruff (state-of-the-art linter)
- Pyright (state-of-the-art type checker; avoid tons of bugs and logical flaws)

### Reproducibility
- Fix the seed !
- Add timestamps everywhere !
- MLFlow, Hydra, WnB
- Create a repository containing all your meeting reports and others documents you produce
- Monitoring is key: visualise your results as much as possible

### Software Engineering
- Git
- Docker
- Singularity
- Spack
- Bash

<br>

## 🧑‍🏫 Teaching
- Prepare your lectures in advance
- Use your website to share materials
