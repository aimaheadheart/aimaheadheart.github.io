# Heart Equity and Access - Responsible Tranplantation

This repository provides a website for the program: Heart Equity and Access - Responsible Tranplantation.

## Important Components of the Project
### Mailist for Internal Communication:

Mailist for internal communication: aimahead-heart@googlegroups.com

Purpose: If you want to email to the whole project team, please send an email to this google group.

### Manager Gmail Account:
Gmail Account: aimaheadheart@gmail.com

Purpose: This account is created to manage the mailist, website and the corresponding GitHub repository. Please use the mailist for project-related communications.

### Version Control and Code Repository:
GitHub Account: aimaheadheart

GitHub URL: https://github.com/aimaheadheart

Purpose: To manage our code, documents, and version control efficiently.

### Project Website:
Website URL: https://aimaheadheart.github.io

Purpose: Serves as the public face of our project, showcasing our work and team.

## Website Structure
### Categories:
- Homepage: Provides our project description.
- People: List all the related people including their images, profiles, affiliations, etc..
- Publications: List all the related publications related to organ transplant.
- Demos: List related demos from our group.
- Activities: Because we may organize some activities later, so put some on the page. We now list one previous tutorial on that, data-centric AI at KDD.
- Collaborations: List the icon of all the institutes, tamu, rice, etc. And will also list the icons of the funding agencies, NIH, AIM-AHEAD.


## Tutorial on Updating the Website
After being set up as a collaborator of the project, you can use your GitHub account to access and modify the repository files to update the website. For the stability of the website, please do not modify folders or files that have not been mentioned without discussion.

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

Lastly, in the folder `/_tabs`, by clicking the "Add file" button and choose "Upload files", you can upload the new `publications.md` file to replace the old one and complete the updating.

![uploadpublications](/assets/img/readme/tabs.png)

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

Lastly, in the folder `/_tabs`, by clicking the "Add file" button and choose "Upload files", you can upload the new `demos.md` file to replace the old one and complete the updating.

![uploaddemos](/assets/img/readme/tabs.png)

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
pin: true   # Should always be true, otherwise the post will be hidden
image:   # add if needed
  path: /assets/img/activities/figure.png   # add if needed
---
```

Please note that the date in the file name of the new activity post and the date at the beginning of the file cannot be in the future, otherwise this post will not be displayed.

Next, you can modify the demo list according to markdown syntax and the template file `/templates/2023-12-01-post-template.md`. If you want to add figures related to the activity post, please put the figure in the folder `/assets/img/activities` and use it following the template.

Lastly, in the folder `/_posts`, by clicking the "Add file" button and choose "Upload files", you can upload the new activity post `YYYY-MM-DD-TITLE.md.` file and complete the updating.

![uploadposts](/assets/img/readme/posts.png)

### More complex markdown functions and syntax
The template file `/templates/2023-12-01-markdown-text-and-typography.md` provides more complex markdown functions and syntax for website updating. Please read it if needed.

  
