---
title: "An article based Latex template for AU PhD thesis"
permalink: /posts/2021-02-27-phdau-article-based-latextemplate
last_modified_at: 2023-12-03
categories:
  - latex
tags:
  - latex
header:
  teaser: "https://github.com/fsn1995/phdau-article-based/blob/master/au%20logo/AU_LOGO/DK/blue/aulogo_dk_var1_blaa.png?raw=true" 
---

A LaTeX template for article based PhD Thesis at Aarhus University. It's adapted from a template from the University of Oslo.
I am improving it very slowly.


<iframe src="https://nbviewer.org/github/AU-ENVS-PhD/phdau-article-based/blob/master/phdau_article_based.pdf" height="800px" width="100%" style="border:none;"></iframe>

# How to use it?
<p>You can download the template at <a href="https://github.com/AU-ENVS-PhD/phdau-article-based/archive/refs/heads/master.zip">GitHub
<img src="https://cdn.icon-icons.com/icons2/692/PNG/512/seo-social-web-network-internet_12_icon-icons.com_61498.png" width="20"/>
</a></p>

Or:
<code class="codeblock">git clone https://github.com/AU-ENVS-PhD/phdau-article-based.git</code>

Then you could open it either locally or online in overleaf.
Feel free to ask questions if any!

# Useful tips

- There's a project logo (deep purple) at the front page. It can be easily modified to your own project or removed. Change the line 194 in `phdau.cls` to your own logo or comment it out.
- Want to have a list of acronyms? Simply add your acronyms to `acronyms.tex` and call the acronyms in any chapters by using `\gls{}` or `\acrfull{}` etc. More can be refered to this [tutorial](https://www.overleaf.com/learn/latex/Glossaries).
- Now it supports displaying orcid id of you or your coauthors if you want. Simply call `\orcid{}` and add your orcid number inside. For pdf readers it will have a clickable link to your orcid profile. See the example in `sections\paperI.tex`.
- Added new function to display keywords. Simply call `\keywords{}` and add your keywords inside. This is because many would like to have a list of keywords at the end of the abstract of the thesis or the papers. 
- Possible to change paper size set to A4, but by default is the book format (17 x 24 cm) which looks better. It is intended for pringting.
- Title page resize is disabled in case of longer title is needed.
- \citet and \citep are now default for citing references. 


<p>This latex template is open source. <a href="https://github.com/AU-ENVS-PhD/phdau-article-based.git">Help me improve it at
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" width="20"/>
<img src="https://cdn.icon-icons.com/icons2/2551/PNG/512/external_link_icon_152846.png" width="10"/>
</a></p>
