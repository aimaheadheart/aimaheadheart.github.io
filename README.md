# Heart Equity and Access - Responsible Tranplantation

This repository provides a website for the program: Heart Equity and Access - Responsible Tranplantation.

## Website Structure
### Categories:
- Homepage: Provides our project description.
- People: List all the related people including their images, profiles, affiliations, etc..
- Publications: List all the related publications related to organ transplant.
- Demos: List related demos from our group.
- Activities: Because we may organize some activities later, so put some on the page. We now list one previous tutorial on that, data-centric AI at KDD.
- Collaborations: List the icon of all the institutes, tamu, rice, etc. And will also list the icons of the funding agencies, NIH, AIM-AHEAD.


## Tutorial on Updating the Website
For the stability of the website, please do not modify folders or files that have not been mentioned without discussion.

### Important folders for website updating
- `/templates`: Contains markdown template files for website updating.
- `/_tabs`: Contains markdown files corresponding to each subpage of the website sidebar.
- `/_posts`: Contains markdown files corresponding to each activity post of the "Activities" subpage.
- `/assets/img/demos`: Contains figures used on the "Demos" subpage.
- `/assets/img/activities`: Contains figures used by activity posts of the "Activities" subpage.

### Updating the "Publications" subpage
We can easily update the "Publications" subpage by modifying the `/_tabs/publications.md` file.

Please do not modify the first five lines of the file, which are not relevant to the publication list:
```
---
# the default layout is 'page'
icon: fas fa-file-contract
order: 2
---
```

Next, you can modify the publication list according to markdown syntax and the template file `/templates/publications-template.md`.

### Updating the "Demos" subpage
We can easily update the "Demos" subpage by modifying the `/_tabs/demos.md` file.

Please do not modify the first five lines of the file, which are not relevant to the demo list:
```
---
# the default layout is 'page'
icon: fas fa-laptop-code
order: 3
---
```

Next, you can modify the demo list according to markdown syntax and the template file `/templates/demos-template.md`. If you want to add figures related to the demo, please put the figure in the folder `/assets/img/demos` and use it following the markdown syntax and the template file.

### Updating the "Activities" subpage
Different from the above, we can update the "Activities" subpage by adding new markdown files to the `/_posts` folder. Figures needed can be add to the `/assets/img/demos` folder.

"Activities" subpage looks like a news list, so we create a separate markdown file for each activity. Please create a new file named `YYYY-MM-DD-TITLE.md` (e.g., `2023-12-01-Hello-World.md`) and put it in the `/_posts` of the root directory. The first part of the file name must use strict date format. 

This time you need to modify the first several lines of the markdown file:
```
---
title: Title of the Activity Post
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE] or [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [tag]   # TAG names should always be lowercase
pin: true   # Should always be true
image:   # add if needed
  path: /assets/img/activities/figure.png   # add if needed
---
```

Next, you can modify the demo list according to markdown syntax and the template file `/templates/2023-12-01-post-template.md`. If you want to add figures related to the activity post, please put the figure in the folder `/assets/img/activities` and use it following the template.

### More complex markdown functions and syntax
The template file `/templates/2023-12-01-markdown-text-and-typography.md` provides more complex markdown functions and syntax for website updating. Please read it if needed.

  
