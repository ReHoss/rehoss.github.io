---
permalink: /guide_ml_research/
title: "Advice and Resources for New Machine Learning Researchers"
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

- **Read papers entirely** this makes you feel you are doing proper research, meticulous and thorough. It also helps you to better understand the research methodology (experiments, metrics, etc.).
Moreover, choose landmark papers in your field to avoid loosing yourself in the vast amount of literature.
 
- **Read paper reviews**.
This is useful to understand what the community expects from a good paper.
This highlights weaknesses of contributions that can be addressed in future/new works.
[OpenReview](https://openreview.net/) is a great platform to access reviews of papers from major ML conferences.

- **Pay attention to [HARKing](https://en.wikipedia.org/wiki/HARKing)** (Hypothesizing After the Results are Known).
This is a common pitfall in research that can lead to misleading conclusions. (It happened to me!)
A nice [paper](https://arxiv.org/abs/1904.07633) on the topic in Deep Learning.

- **Know reviewers instructions** and criteria for conferences/journals you are submitting to. This helps you understand what is expected from your work. ICML reviewer guidelines [here](https://icml.cc/Conferences/2025/ReviewerInstructions).

- **Review papers for journals or conferences**

- **Try to keep a research journal** to document your ideas, experiments, and findings.
Be **verbose**! This provides context for humans and AIs. For now, the main vector of information with AI assistants is natural language (text).

- Follow the _Observation - Question/Problem - Hypothesis/Method - Experiment - Analysis - Conclusion_ framework for structuring your research process.
This discipline helps in maintaining clarity and rigor throughout your research journey. Prevents harking and other biases.

### Bibliography
- Store your bibliography files and construct your **OWN** library
- Use Zotero or similar tools (Google Drive) to construct this library
- I personally use Google Drive synchronised on [PDF Expert](https://pdfexpert.com/) which allows to annotate documents with automatic synchronisation.
The latter tool greatly simplifies scanning and attaching handwritten notes to articles or books.


### Writing
- Microsoft Research (S. P. Jones) [presentation](https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper/) on how to write a great paper.
- Ask your local academic writing center for help.
- Write *before* using AI tools.

#### Software
- Latex
- Typst (promising tool)


### Talks, presentations and posters
- One minute by slide rule.
  Target a duration of 90% of the total time for your talk.
  This leaves time for unexpected events.
- Don't try to put the same level of details in a talk as in a paper.
  Try to be clear and transmit the essential ideas.
- If you are an intern, consider yourself as a researcher and play this role in your presentations.
- Mention your sponsors and collaborators.
- Add a QR code to your slides/poster to link to your paper or website.

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
- StackExchange (e.g. [Academia StackExchange](https://academia.stackexchange.com/))
- X
- YouTube

### Blog articles
Personal blogs and articles are always a great source of inspiration and knowledge.
Some notable mentions are:

- P. Kidger [blog](https://kidger.site/thoughts/) and in particular his advice on [how to achieve success in ML research](https://kidger.site/thoughts/just-know-stuff/).
- J. Schulman [blog](http://joschu.net/blog.html), in particular his [guide on ML research](http://joschu.net/blog/opinionated-guide-ml-research.html).
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
- [Ruff](https://docs.astral.sh/ruff/) (state-of-the-art linter)
- [Pyright](https://microsoft.github.io/pyright/#/) (state-of-the-art type checker; avoid tons of bugs and logical flaws)

### Reproducibility
- Fix the seed !
- Use configuration files (YAML, JSON, TOML, etc.). Possibly use schemas to validate them.
- Add timestamps everywhere !
- Experiment trackers MLFlow, [Hydra](https://hydra.cc/), [Weights & Biases](https://wandb.ai/site)
- Create a repository containing all your meeting reports and others documents you produce
- Monitoring is key: visualise your results as much as possible

### Software Engineering
- Git
- Docker
- [Singularity](https://docs.sylabs.io/guides/4.3/user-guide/) (containerization for HPC)
- [Spack](https://spack.io/) (package manager for HPC)
- Bash
- [Slurm](https://slurm.schedmd.com/documentation.html)

<br>

## 🧑‍🏫 Teaching
- Prepare your lectures in advance
- Use your website to share materials
