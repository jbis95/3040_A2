# How to Host Your Resume on GitHub Pages

### Audience
Welcome to a tutorial for those who would like to use markdown to write a resume and publish on GitHub Pages with a Jekyll theme to make it stand out to future employers. 

### Prerequisites
This tutorial assumes basic knowledge of GitHub commands such as ```push```, ```pull```, ```init```, ```clone```, and ```commit```. No previous knowledge of Atom, Markdown, and Jekyll are required.

### Instruction
Before beginning, start in order from Markdown, to GitHub Pages and then Jekyll.

##### Markdown
To start writing in markdown, it is necessary to download a text editor that supports markdown. For example, Atom is a modern and popular choice for markdown because of its support for multiple markdown flavours. Atom allows to see a live preview of the markdown in real time while typing which is very useful while writing.

1. ###### Download Atom
Simply visit [Atom.io](Atom.io) to download and install.

2. ###### Open a project and file
In initial launch of Atom, Atom requires choosing a location for a project and then all files created are in that directory.

3. ###### Tips in markdown
Some useful things to know about markdown are the following:

| Feature      | Markdown     | Result   |
|:-------------:|:-------------:|:---------:|
| Bold Text     | \*\*Bold\*\* | **Bold** |
| Heading 1      | \# Heading 1      | No Preview Available |
| Links | \[Links](Enter url)     | [Links](#)
| New Line | "Double Space" or "Enter" | No Preview Available |

Markdown allows as many headings, just add the number of \# for the heading level.

Note that for a new line, GitHub Flavoured Markdown (GFM) requires "Enter" in between lines instead of "Double Space".

4. ###### Writing the resume
Most likely have a resume is done in Word, so to translate everything in markdown, type the resume using some of the tips in step 3 and format it until it looks good.

##### GitHub Pages
In a GitHub account create a repository. Once that is done, do the following:

1. ###### Find GitHub Pages
In the repository go to ```Settings -> Scroll down to GitHub Pages``` 

2. ###### Add a Jekyll theme
GitHub has a selection of Jekyll themes to choose from and whenever committing a theme, an index.md and \_config.yml are generated. There is also the option of downloading any Jekyll theme from other sources which then push the files in the repository. 

3. ###### Writing your resume
Open index.md, this markdown file is where you write your resume. Anything typed here will appear publicly online so be cautious not to put very sensitive information.

4. ###### Optionally add more links
This can be done in the file ```_config.yml``` which allows have multiple pages linked together on GitHub Pages. It is optional since this tutorial deals with a one page resume.  

5. ###### Viewing your page
Once everything is committed and pushed to GitHub, access the GitHub Pages site by going to ```https://[GitHub user ID].github.io/[repository name]/```.

Voila! The resume is now live online.


##### Jekyll Themes
This section shows how to modify the Jekyll Front Matter.

The Jekyll Front Matter is stored in the ```_config.yml``` file. At the moment the resume displays the ```repository name``` instead of ```resume```. To change the title, insert the following:

```title: RESUME```

and that is all!

### More resources

#### Further Reading

#### FAQ
1. Do these tools work on any platform?  
Yes/No, writing in markdown can be done on any platform even mobile devices, GitHub I found it easier on a desktop operating system but you can still write the README directly on GitHub and also change the Jekyll theme that is supported by GitHub Pages. Atom on the other hand only supports Windows, MacOS and Linux, no mobile devices. The developer are not interested in mobile at the moment.

2. What happens if I change themes later?  
Good news! Everything stays where you expect them to be. There may be some problems with tables because of the fact that markdown has many different flavours and no standard for it. To be safe it is recommended to stay with a Jekyll theme that is fully compatible with GitHub Pages.

### Authors and Acknowledgments
Thank you to my group partner Naol for feedback on this assignment.
Also the Jekyll theme is the slate theme on the list of GitHub Pages themes.
