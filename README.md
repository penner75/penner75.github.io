# How to upload your Markdown Resume with GitHub Pages, and apply a Jekyll theme

## Description of Intended Audience

*Audience*:

| Technology     | Atom | Markdown | GitHub | Jekyll |
| -------------- | ---- | -------- | ------ | ------ |
| **Experience** | none | some     | some   | none   |

*Venue*: README file within GitHub Pages

*Purpose*: Write a resume using Markdown, Format the resume with a Jekyll theme, and host resume (for free) on GitHub Pages.

*Additional purpose*: Increase experience and confidence in technical writing tools: Markdown, Jekyll, and GitHub Pages.

*Desired Reaction*: Reader will be interested in GitHub pages, and want to try hosting their own resume

*Vocabulary*: Simple

*Tone*: Casual, Polite

## Prerequisites

- A GitHub account

- A Resume written in Markdown

## Instructions

### i. Create GitHub Pages Repository

1. Sign into your GitHub account
2. Click "new repository." This option will be on the left side of the homepage
3. Give the repository the name "yourUserName".github.io For example, my username is penner75, so I would name mine penner75.github.io
4. Scroll down to the bottom of the page and click the green "Create Repository" button

### ii. Upload Resume

1. Go to your "repository"  under "yourUserName"/"yourUserName".github.io (this will already be open if you just finished step **ii**)

   eg.penner75/penner75.github.io

2. Click "upload files" in the center of the page

3. Select your resume file (should be a markdown file)

4. Change the name of your resume file to "index.md"

### iii. Change Theme

1. Click on settings

2. Under settings (the rightmost option found underneath your repository title), click "change Jekyll theme"

3. Choose a Jekyll theme from the options available to you

4. Confirm your selection by clicking commit at the bottom of the page

5. Click on your index.md file

6. Click "Edit File"

7. At the top of your index.md file, insert  

   "---

   layout: default;

   ---"

### iv.  Revise Theme

1. Go to your newly created "config.yml" file. It will be in your main folder, 

2. Click "edit this file" 

3. Edit this file by adding a title. Insert the following code at the top, replacing (My Title!) with your title

   title:(My Title!)

## Resources

For learning about GitHub pages:http://jmcglone.com/guides/github-pages/

For learning about Markdown:https://www.markdowntutorial.com/

## Authors and Acknowledgements (template authors and group members)

Thank you to my group members, Brendan Stothers and Proyash Saha. Thank you to the many contributors of the Cayman Jekyll Theme as well.

## FAQs 

*Why isn't my page showing up*?

Check to make sure that your resume has been renamed to "index.md", and that your repository is named "(yourUserName).github.io". If you have double-checked that both of these values are correct, wait a few minutes, as there can be a bit of a delay.

*How Do I host another webpage?*

GitHub Pages only allows for one page to be hosted for free per user, so you can either upgrade your account, or create alternative accounts for alternative webpages.

