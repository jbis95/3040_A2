# How to Host Your Resume on GitHub Pages

### Audience
Welcome to a tutorial for those who would like to use Markdown to write a resume. In addition, publish it on GitHub Pages and applying Jekyll theme to make it stand out to future employers. 

### Prerequisites
This tutorial assumes basic knowledge of GitHub commands such as ```push```, ```pull```, ```init```, ```clone```, and ```commit```. No previous knowledge of Atom, Markdown, and Jekyll are required.

### Instruction

#### Step 1: Edit Resume with Markdown
To write things in Markdown, download a text editor such as [Atom](https://atom.io). Atom is light weight, modern and supports many different flavours of Markdown. The flavour of choice is GitHub Falvoured Markdown (GFM) because it is what GitHub uses and integrates well with Jekyll. To get started using Markdown, go visit this [tutorial](https://www.markdowntutorial.com/) to learn some basic Markdown before continuing. In addition, below is a table of useful Markdown features that are frequenly used to write a resume.

| Feature      | Markdown     | Result   |
|:-------------:|:-------------:|:---------:|
| Bold Text     | \*\*Bold\*\* | **Bold** |
| Heading 1      | \# Heading 1      | No Preview Available |
| Links | \[Links](Enter url)     | [Links](#)
| New Line | "Double Space" or "Enter" | No Preview Available |

Most likely a resume is written in Word, so to convert into Markdown, type in the whole resume and format it to make it look like in Word.

#### Step 2: Host Resume on GitHub Pages
GitHub Pages is a feature in GitHub that allows hosting a static site for free! All you need is a Markdown file and a GitHub account. Exactly one site per GitHub account is allowed which makes it perfect to host a resume to impress future employers. At the end of this step the Markdown file will become public and render at a url specified later. The resume will be viewable exactly how the preview window in Atom is shown.

##### 1. Login to GitHub
Go to ```github.com``` and enter a username and a password.

##### 2. Create a new repository
On the main page, create a new repository. The name of the repository matters as stated in the next step. All the files created will be stored in this repository and accessible to anyone.

##### 3. Name the repository [user].github.io
The name of the repository must have the name ```[user].github.io``` where ```user``` is the username of the GitHub account. If the repository has a different name, GitHub Pages will not work with the url that is given to every GitHub account to visit the site.

##### 4. Copy/Paste resume into index.md
GitHub Pages requires the file that renders the page to be named ```index.md``` which is similar to other web servers. Copy and paste the resume in Markdown into this file, save it and push. Then your resume will show in raw Markdown at ```[user].github.io```. The next step will allow the resume to look prettier by adding a theme.

#### Step 3: Add a Jekyll theme
Jekyll is the most popular static site generator that is well integrated into GitHub Pages. Its popularity invites a well known community of designers and developers to design and build themes that anyone can use. GitHub has chosen several themes that are made to be compatible with GitHub Pages. Simply go to ```Settings``` and scroll down to Github Pages and so to add and change themes is just one click of a button. Furthermore, choosing a theme from another source will also work by forking a themes repository and modifying the files to fit the resume.

#### Step 4: View your resume online
At this stage, the resume is ready to be shown to world! To visit a GitHub Pages site, simply enter ```[user].github.io``` in any browser. GitHub Pages will render the Markdown file with the Jekyll theme for anyone to see. One more thing is that the title of the page will be the same as the repository. To change this, open ```_config.yml``` and add the line ```title: RESUME```. This file allows you to do many other things that are outside of this tutorial. For information on how to do more advanced things with Github pages, start with this [documentation](https://jekyllrb.com/docs/configuration/). 

### More resources

#### Further Reading
Here are some links to other useful resources for Markdown, GitHub Pages, and Jekyll.

https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll

https://www.markdownguide.org/cheat-sheet

https://jekyllrb.com/tutorials/home/


#### FAQ
1. Do these tools work on any platform?  
Yes/No, writing in markdown can be done on any platform even mobile devices, GitHub I found it easier on a desktop operating system but you can still write the README directly on GitHub and also change the Jekyll theme that is supported by GitHub Pages. Atom on the other hand only supports Windows, MacOS and Linux, no mobile devices. The developer are not interested in mobile at the moment.

2. What happens if I change themes later?  
Good news! Everything stays where you expect them to be. There may be some problems with tables because of the fact that Markdown has many different flavours and no standard for it. To be safe it is recommended to stay with a Jekyll theme that is fully compatible with GitHub Pages.

### Authors and Acknowledgments
Thank you to my group partner Naol for feedback on this assignment and Ms. Penner for improving the structure of the README.

Also the Jekyll theme is the slate theme on the list of GitHub Pages themes.
