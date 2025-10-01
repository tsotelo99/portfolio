---
layout: base
title: Editing your site
author: Fred Gibbs
date: 2019-10-03
---

# {{page.title}}

<!--
### Table of Contents
* TOC
{:toc}
-->

Here are the basic process for editing a page and adding a new page. All steps start from your repository home page in GitHub.

## Editing a page
Let's make a simple change to the homepage (your `index.md` file).
- Click on the `index.md` file.
- Click on the edit icon (looks like a pencil)
- Make some change to the text.
- Hit the green Commit button near the bottom of the page.
- Wait a few minutes and refresh your webpage.

## Add a new page
Of course you'll want to add your own pages. The GitHub website does not have an easy way to duplicate files. But we can do it manually.
- Click on a file that is a similar kind of page to what you want to create. 
- Click on the `Code` icon for that page.
- Copy the YML header to your clipboard, including the two sets of `---` on the top and bottom 
- Click the `Add file` button
- Type in the filename, including a `.md` extension
- Paste your YML header on your new page
- Hit the green Commit button near the bottom of the page

---

## Edit the navigation bar
Now we need to add the new page to the navigation bar
- Click on the `_includes` directory
- Click on `nav.html`
- Click on the edit icon (looks like a pencil)
- Duplicate (via copy and paste) on of the lines that contains a link to a page on your site
- Replace the old link with the name of the page you just created but WITHOUT the `.md` extension
- Hit the green Commit button near the bottom of the page

---

## Moving files
- Go into edit mode for the file you want to move
- Click on the filename at the top of the edit pane --- this is called the file PATH
- You can make this path into whatever you want `/` to create new folders.
- If you in the edit textbox and you want to edit something that appears before the textbox, just put the curson on the far left of the textbox and hit backspace or delete and you'll be able to edit it. 