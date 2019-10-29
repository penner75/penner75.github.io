# How to upload your Markdown Resume with GitHub Pages, and apply a Jekyll theme

## Description of Intended Audience

*Audience*:

- no experience in Atom
- no experience in Markdown
- some experience in GitHub
- no experience with Jekyll

*Venue*: README file within GitHub Pages

*Purpose*: Write a resume using Markdown, Format the resume with a Jekyll theme, and host resume (for free) on GitHub Pages.

*Additional purpose*: Increase experience and confidence in technical writing tools: Markdown, Jekyll, and GitHub Pages.

*Desired Reaction*: Reader will be interested in utilizing GitHub pages to host a webpage

*Vocabulary*: Simple

*Tone*: Polite, Casual

## Prerequisites

- A GitHub account

- A Resume written in Markdown

## Instructions

![](Gif Stuff/Entire Process.gif)

### Create GitHub Pages Repository

1. click "new repository"
2. give the repository the name (yourUserName).github.io For example, my username is penner75, so I would name mine penner75.github.io

### Upload Resume

1. Click "upload files"
2. Select your resume file (should be a markdown file)
3. Change the name of your resume file to "index.md"

### Change Theme

1. Under settings, click "change Jekyll theme"

2. Choose a Jekyll theme

3. Confirm your selection by clicking commit at the bottom of the page

4. Now edit your index.md file.

   At the top of your index.md file, insert  

   "---

   layout: default;

   ---"

### Revise Theme

1. In your main folder, there should now be a filed called "config.yml"
2. Edit this file, and add a title. For instance: title:My Resume!;

## Resources

http://jmcglone.com/guides/github-pages/

## Authors and Acknowledgements (template authors and group members)

Thank you to my group members, Brendan Stothers and Proyash Saha. Thank you to the authors of the Cayman jekyll Theme as well.

## FAQs (at least 2)

*Why isn't my page showing up?*

Check to make sure that your resume has been renamed to "index.md", and that your repository is named "(yourUserName).github.io".

*Why isn't my theme working?*

Make sure that you did not forget to change the front matter for your index.md file. If you have selected a default layout, check your config file to ensure that your theme is selected. If you have completed both these steps and the theme is not showing up, wait about 5 minutes and check your website again. Sometimes there is a bit of a delay.
