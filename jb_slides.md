<!-- .slide: data-transition="fade-in slide-out" data-background-color="#CFECEC" -->
## UBC Library Research Commons

A multidisciplinary hub supporting research endeavours, partnerships, and education <!-- .element: class="fragment semi-fade-out" data-fragment-index="1" -->

Workshops developed and presented by librarians and graduate academic assistants (GAAs) <!-- .element: class="fragment" data-fragment-index="1" -->

notes: Eugene and I work at the UBC Library Research Commons, a multidisciplinary hub that supports researchin general, including through workshops and consultations that help faculty and students develop research-enabling skills. 

The Research Commons developed out of a peer support model, with many of its services offered by graduate students. Graduate Academic Assistants continue to be involved in many Research Commons activities: the workshops we will talk about today are a collaboration between librarians and GAAs - both in their development and delivery. 

---
### Distributed development 

- Many perspectives -> better content <!-- .element: class="fragment" -->
- Student employees = high turnover <!-- .element: class="fragment" style="color:#7E3517" -->
- Hard to remain consistent <!-- .element: class="fragment" style="color:#7E3517" -->


notes: I would argue that this collaborative workshop development model has worked well for us, and that incorporating the perspectives and insights of GAAs coming from many academic backgrounds (not just the Library and Information Science stream) has improved our content overall. But collaboration of this type  also introduces some challenges.

An obvious challenge is that graduate student involvement usually means higher turnover as students come and go. Onboarding new students and managing the transitions requires coordination as each new persong brings their own habits and preferences to the table. We're also split into smaller teams, each responsible for a certain area: Data Analysis and visualization in my case and RDM for Eugene. Needs and preferences also differ between teams.  also p content teams

---
### The OER vision

- Open and reusable
- Collaborative development
- Consistent presentation
- Using free tools

notes: Collaborative, using freely available tools accessible outside the Library and the university
Use tools employed by our teams
Lower barriers to access and remixing

---
### Chosen software/platforms
<br/>

| software | function |
| --- | --- |
| Git | _version control_ |
| GitHub | _collaboration/distribution_ |
| GitHub Pages | _presentation (webpages)_ |
| reveal.js | _presentation (slides)_ |

notes: So we selected these tools
The selection of these tools is opportunistic. Is it the only obvious choice: no. Would I choose it again: yes. But two big factors in selecting these: internal skill development, and existing champions/experience on the team.  
 
- Existing experience on the team with Git and Github
- Already in use by members of the team for similar cases (GIS workshops)
	- This included workshop content in repo and Reveal.js slides via GH Pages

- Inspiration from the Carpentries' OER model
- Philosophical desire to lower barriers to access and remixing
- Not a UBC-specific platform / approach
- Content requires only a browser window to access and is downloadable for bad connections
- Student employees need to have access to content, not able to login into Intranets-   

---
<!-- .slide: data-transition="slide-in fade-out" -->
### Rationale

- Strengthen team's skills
- Content in plain text files 
- No software costs
- Better workflow management
 
notes:
- New team, new desire to upskill and experiment with new workflows
- Goal to better support technical consults
- Text-based approach easy to move, remix, repurpose
- Better ownership, collaboration, and maintenance workflows with growth in size of unit
- Currently, Github Pages is free and unlimited for our use case


---
<!-- .slide: data-transition="fade-in slide-out" data-background-color="#CFECEC" -->
## The workflow

notes: An overview of the workflow for creating and publishing UBC Library Research Commons workshop websites.

---
        <div style="width: 28%; font-size: 0.8em; padding: 2%; text-align: left; position: relative; float: left">
		  <h3>Setup</h3>
          <ul> 
			<li>GitHub account for each contributor</li>
			<li>GitHub <em>organization</em> for Research Commons</li>
          </ul>
</div>

        <div class="fragment" style="width: 28%; font-size: 0.8em; padding: 2%; text-align: left; position: relative; float: left">
          <h3>Content</h3>
          <ul>
		  <li>Markdown</li>
		<li>HTML/CSS <br/><em>(optional)</em></li>
          </ul>
		  </div>


        </div>
        <div class="fragment" style="width: 28%; font-size: 0.8em; padding: 2%; text-align: left; position: relative; float: left">
          <h3>Skills</h3>
          <ul>
			<li>Markdown <em>(everyone)</em></li>
			<li>Git/GitHub <em>(everyone)</em></li>
			<li>GitHub Pages <em>(someone)</em></li>
          </ul>
		</div>


notes: The requirements for our workflow are relatively simple. GitHub is the only platform that's a must. Each person who will contriubute to or manage the content should have their own GitHub account.

We gather the individual accounts under a GitHub organization, which makes it relatively easy to add or revoke rights as collaborators come and go. All our repositories are "owned" by the organization, not by individual acconts.  

The workshop source material is written in Markdown. Many workshop sites include the presentation slides - these can be added to the repository in any format, but doing them in reveal.js provides more flexibility for presenting them within the workshop site.

The skills required for authoring content are familiarity with Markdown and GitHub. That's a relatively low barrier but those skills aren't universal and getting the whole team comfortable with the tools can take some work.

In additon to the basic authoring skills, someone on the team will need to understand how Jekyll works, but that can be just one person to handle the theme and configuration options.</p>

---

From Markdown content...

```markdown

# Why is file naming important?
{: .no_toc }

<p style="margin-top:20px;margin-bottom:25px">
Creating a well-organized hierarchy of files with clear naming conventions is an important part of improving your research process. This is especially important if you are working with large data sets and complex output files or coordinating with multiple people at multiple institutions. There are many ways to structure your folders, and multiple naming conventions you can use. The key is <b>consistency</b>. Make your file names descriptive, and include information about dates and versioning. The best practice is to consult with your lab or with your co-workers to develop a naming schema that everyone is willing to follow consistently.
</p>

Looking for a cheat sheet? Check out our <a href="https://osf.io/pfweq" target="_blank">one-pager</a>!
{: .note}

<details open markdown="block">
 <summary>
   Table of contents
 </summary>
 {: .text-delta }
- TOC
{:toc}
</details>

 ---

What do you think about the following file names?
- 10_data 2.txt
- figure 1.png
- final revision.docx
- Lily's schedule&plan 2022Jul9.xlsx

```

<span>Excerpt from <https://github.com/ubc-library-rc/rdm/blob/rdm-pages/content/01_file_naming.md></span> <!--.element: style="font-size:24px; font-style: italic; opacity: 0.8" -->


notes: Here's an example of a Markdown file for the front page of an RDM workshop about file naming.

---
<!-- .slide: data-background-iframe="https://ubc-library-rc.github.io/rdm/content/01_file_naming.html" data-backround-interactive data-background-transition="zoom" -->

...to published workshop site <!-- .element: style="position: absolute; left: 65%; top: -300px; width: 30%; color: white; background-color: grey; opacity: 0.8; font-size: 0.8em" -->

          
notes: And this is the website for the corresponding workshop created by Eugene and the GAAs he works with. The layout is simple and consistent, with visual elements common to all Research Commons workshops, including the navigation menu on the left. 

---
<!-- .slide: data-auto-animate data-transition="none" -->
Each workshop/series is a GitHub repository

![Screenshot of GitHub interface](media/github-repo.png) <!-- .element: class="fragment fade-in-then-semi-out" data-fragment-index="1" -->

![Screenshot of file list](media/github-repo-content.png) <!-- .element: style="position: absolute; left: 55%; top: 15%" class="fragment" -->


notes: Each workshop we publish in this way has its own GitHub repository in the Research Commons GitHub organization.
Here's a snapshot of the repository for the Docker workshop. At the top level is the index.md file corresponding to the website front page, as well as the config yaml file, which we'll look at in more detail soon.
In the "content" folder are multiple markdown files; each becomes its own page on the workshop site. This folder organization is useful but not required: the markdown files can be anywhere in the repository. How they're presented on the site is governed by a yaml header in each file, not by the structure of the repository.
Those familiar with Jekyll will notice that there aren't many Jekyll-related files in this repo.

---
<!-- .slide: data-transition="fade-in slide-out" -->

Website theme in its own GitHub repository

![GitHub screenshopt](media/github-template.png)

<span>The Research Commons uses a modified version of the [Just the Docs](https://github.com/pmarsceill/just-the-docs) Jekyll theme</span> <!-- .element: style="font-size:24px; font-style: italic; opacity: 0.8" -->

Notes: That's because in our workflow the Jekyll theme lives in a separate repository. This improves consistency across our workshop sites and makes updates and upgrades easier.

The Jekyll theme we use in the Research Commons is based on the Just the Docs theme with some local changes to the layout and css files. This theme-repository is called upon whenever one of the workshop sites is built (whether by GitHub pages or in a local Jekyll environment).

---
<!-- .slide: data-transition="slide-in none-out" -->

Applying theme to workshop sites: **config.yml**

```yaml <!-- .element: class="fragment" -->
title: Intro to Docker
remote_theme: ubc-library-rc/rc-workshop-template
github_repo_url: "https://github.com/ubc-library-rc/intro-docker/"

# license information for workshop content
license_name: "Creative Commons Attribution 4.0 International License"
license_url: "http://creativecommons.org/licenses/by/4.0/"
license_image_url: "https://i.creativecommons.org/l/by/4.0/88x31.png"

# required for building jekyll site locally
plugins:
- jekyll-remote-theme
- jekyll-seo-tag
```

Notes: The link between the content repository and the theme repository is established in the config yaml file.

The _remote theme_ points to our theme repo and is all that's needed to stitch the workshop repository to the theme. The config file also contains copyright information.
At the bottom is is a section that applies to those who run Jekyll locally to test the site before pushing to GitHub. Other settings you'd expect to find in a config file are covered by the config file associated with the theme repository.

---
<!-- .slide: data-transition="fade" -->
<span>Instructions and documentation<br/>
<https://ubc-library-rc.github.io/rc-workshop-template/></span> <!-- .element: style="margin-top: 30px; font-size:smaller"> -->

Notes: A challenge with any workflow in a team environment is getting everyone on board, doing things in roughly the same way. To help with this the Research Commons theme repository is itself rendered as a GitHub pages site with step-by-step instructions for workshop authors.

---
<!-- .slide: data-transition="fade-in slide-out" -->
### Improvement and maintenance

- Coordinated content review 
- _GitHub Issues_ for specific changes
- _Pull requests_ for community contributions

notes: Describe the repository and tracking of content review. Briefly describe the functionality for GitHub issues, and how a platform designed for identifying and documenting the development of bug fixes and feature requests has many affordances for maintaining and improving our workshops in a group setting. Finally, note that through pull requests, members of the community and workshop participants who are familiar with GitHub can propose improvements.   

---
<!-- .slide: data-transition="slide-in fade-out" -->
### Does it work? A reality-check
<div class="fragment" style="float:left; font-size: 0.8em; margin: 0 3%; width:42%; position: relative">
<h3 style="color: DarkGreen">Pros</h3>
<ul>
<li>Skill development</li>
<li>Sustainable formats</li>
<li>Consistent presentation</li>
<li>Community contribution</li>
<li>Preserve content history</li>
</ul>
</div>
<div class="fragment" style="float:left; width:42%; margin: 0 3%; font-size: 0.8em; position: relative">
<h3 style="color: DarkOrange">Cautions</h3>
<ul>
<li>Steep learning curve</li>
<li>Dependent on GitHub</li>
<li>Requires upkeep</li>
</ul>
</div>

notes: So, after several years does the implementation live up to the promise? Describe pros and cons. Provide examples of practical things you've done that you couldn't have otherwise. Be honest about the commitment required for poeple who are new to the tools. When GitHub changes a workflow, so do we. 

Pros:
We develop fluency with the tools that many researchers use, and by collaborating on these platforms we establish a higher baseline using the very text file formats that we often encourage researchers to use. We provide our material with a constent presentation, making it easier to both present and navigate the content. 

Cons: 
At times I wonder whether the time it takes to learn the tools and work in this environment is worth the effort. In particular I'm thinking about making slides in reveal.js, like the slide deck we're using for this presentation. People with limited markdown, html, and css may find it _much_ easier to collaborate on slides in Google Docs, for example.  

---
<!-- .slide: data-transition="fade-in slide-out" data-background-color="#CFECEC" -->
## Research Data Management OERs
