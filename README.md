# How to Host Your Resume on GitHub Pages

### Who is this for?
Welcome to a tutorial for those who would like to use markdown to write a resume and publish on GitHub Pages with a Jekyll theme to make it stand out to future employers. 

### Prerequisites
This tutorial assumes that the user has basic knowledge of GitHub usage such as push, pull, init, clone, and commit. No previous knowledge of Atom, Markdown, and Jekyll are required.

### Instructions
Before we begin, we will start to show in order Markdown, GitHub Pages and then Jekyll.

##### Markdown
To start writing in markdown, it is necessary to download a text editor that supports markdown. For example, Atom is a modern and popular choice for markdown and is the one of choice for me. Atom allows you to see the results of the markdown in real time while you are typing which I find it useful while writing.

1. ###### Download Atom
Simply visit [Atom.io](Atom.io) and download for your platform.

2. ###### Open a project and file
When you first open Atom, Atom requires you to choose a location for your project and then create files in the directory.

3. ###### Tips in markdown
Some useful things to know about markdown are the following:

| Feature      | Markdown     | Result   |
|:-------------:|:-------------:|:---------:|
| Bold Text     | \*\*Bold\*\* | **Bold** |
| Heading 1      | \# Heading 1      | No Preview Available |
| Links | \[Links](Enter url)     | [Links](#)
| New Line | "Double Space" | No Preview Available |

Markdown allows as many headings as you want, just add the number of \# for the heading level you need.

4. ###### Writing the resume
You most likely have your resume done in Word, so to translate everything in markdown, type your resume using some of the tips in step 3.

##### GitHub Pages
In GitHub we assume the user has an existing account and knows how to create a repository. Once that is done, do the following:

1. ###### Go to repository
Go to your repository -> Settings -> Scroll down to GitHub Pages  

2. ###### Add a Jekyll theme
GitHub has a selection of Jekyll themes to choose from and whenever you commit a theme, an index.md and \_config.yml is generated. Optionally there is the option of downloading any Jekyll theme from other sources which then you push the theme in your repository. 

3. ###### Modify index.md
This file is where you write your resume in markdown will be stored.  

4. ###### Optionally modify \_config.yml
This file allows to link multiple pages together on your GitHub Pages site. It is optional since in this tutorial we are dealing with a one page resume.  

5. ###### Commit and Push your changes

5. ###### Viewing your page
To view your GitHub Pages site, go to ```https://[GitHub user ID].github.io/[repository name]/```


##### Jekyll Themes
This section shows how to modify the Jekyll Front Matter.

### More resources

### Authors and Acknowledgments
Thank you to my group partner Naol for feedback on this assignment.
Also the Jekyll theme is the slate theme on the list of GitHub Pages themes.

### FAQ
1. Do these tools work on any platform?  
Yes/No, writing in markdown can be done on any platform even mobile devices, GitHub I found it easier on a desktop operating system but you can still write the README directly on GitHub and also change the Jekyll theme that is supported by GitHub Pages. Atom on the other hand only supports Windows, MacOS and Linux, no mobile devices. The developer are not interested in mobile at the moment.

2. What happens if I change themes later?  
Good news! Everything stays where you expect them to be. There may be some problems with tables because of the fact that markdown has many different flavours and no standard for it. To be safe it is recommended to stay with a Jekyll theme that is fully compatible with GitHub Pages.
