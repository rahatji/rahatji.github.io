## Hosting a Markdown-formatted Resume on GitHub Pages

**Purpose:** 
A guide on creating a static website to host a resume using Markdown, GitHub Pages, and Jekyll, inspired by the principles outlined in Andrew Etter's book "Modern Technical Writing."

### Summary
- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [More Resources](#more-resources)
- [Authors and Acknowledgements](#authors-and-acknowledgments)
- [FAQ](#faq)


### Prerequisites

- Git Hub account
- a resume formatted in markdown
- How to use git

#### Markdown-Formatted Resume
Markdown, a simple markup language created by John Gruber and Aaron Swartz in 2004, offers a straightforward way to generate stylized content in a plain text editor. The primary goal of Markdown is to empower individuals to write in a plain text format that is easy to both read and write.

#### Why use Markdown? 

>As per Andrew Etter's "Modern Technical Writing," a "Lightweight Markup Language" proves advantageous and uncomplicated in website development. It features a minimal learning curve and employs straightforward syntax. Additionally, modifications to the file can be easily executed using a standard text editor.


#### GitHub Account
Creating an online resume website requires having an account on GitHub or Codeberg. In my case, I opted for GitHub to host my resume.

#### Jekyll
Jekyll, a static page generator for websites, utilizes content written in a markup language and allows flexibility in design to build static websites. The website's appearance, URLs, and presented information are all customizable. Theme selection is available from a variety of options [here](https://pages.github.com/themes/). To apply a theme, add a '_config.yml' file containing a straightforward Jekyll theme to your repository, following the instructions provided [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).

In my case I used this following theme:
`_config.yml`
```
theme: jekyll-theme-architect
```
### Instructions

#### 1. Resume 
Markdown is the most widely used lightweight markup language in the world, and there are a number of software tools that may help you get the most out of it, including: 

>* [Visual Studio Code](https://code.visualstudio.com/)(For Mac os ,Windows and Linux)
>* [Atom](https://atom.en.uptodown.com/windows) (windows)
>* [iA Writer](https://ia.net/writer) (Mac OS)
>* [ReText](https://codepre.com/how-to-install-retext-restructuredtext-editor-in-ubuntu-a-markdown-editor-for-linux.html) (Linux)   

**Notes** 

- If you decide to host your resume on GitHub, make sure to utilize the [GitHub Markdown Doc](https://guides.github.com/features/mastering-markdown/). This version of Markdown has been specifically tailored to the GitHub infrastructure. To ensure optimal performance and avoid rendering issues when publishing your resume on GitHub, refrain from using any other Markdown version.
- name and save your resume file as `index.md` .

#### 2. GitHub Account 
>In " _Modern Technical Writing_," Etter recommends the adoption of Distributed Version Control Systems (DVCS) such as Git and Mercurial over centralized systems. These systems allow offline work and contribute to improved overall performance. Consolidating all work, including documentation, in a single location is advantageous due to the widespread adoption of this technology by the majority of developers.


#### Installing Git
1. Visit and follow instructions on this [link](https://github.com/git-guides/install-git) for installiing git in your system



#### Creating an Account 
1. Go to [GitHub](https://github.com/)
2. Select Sign up
3. Enter your email first and then set your password
4. Then enter your username
5. Verify your account from your email address and you are all set

#### Create a New Repository 
1. Go to [GitHub](https://github.com/)
2. Sign in to your account
3. Click on Repositories 
3. Click the New Button - **Green Button on the top left of the screen**
4. Name you repository using the format - *YourUserName*.github.io
5. Then click on Create repository - **Bottom of the screen**
 

**Note:** The naming convention for the repository (YourUserName.github.io) is important as it is the default format recognized by GitHub Pages for personal websites.

#### Upload your Resume in the repository
After you have created your repository
1. Click "Add file " and it will give a drop down menu
2. Select "Upload files" from the drop down menu
3. Drag and drop your 'index.md' file from your computer.
4. You can also select "Choose your files' and it will let you select and upload
    your desired 'idex.md' file from your computer's local directry.
5. Then click on the green "Commit changes" located at the bottom to ulpoad your 'index.md' file.

**Note:** You resume must be named as index.md


#### 3. Hosting your Resume using GitHub Pages
>As per Etter in "Modern Technical Writing," static websites are recommended for documentation due to their independence from dependencies and ease of deployment. GitHub Pages, in alignment with this philosophy, utilizes Jekyll to host static content, offering the added advantage of applying themes to enhance the appearance and professionalism of documentation. 

1. Go to your repository and click on Settings
2. Find the **Pages** section from the sidebar
3. Make sure that the 'main' branch is chosen as source and **Save**

#### Conclusion 
You have completed hosting your resume online on GitHub .

Your resuume will look like something like this when you go to a url using the follwing URL address rule:
  *YourUserName*.github.io 
  
#### More Resources
* [Basic Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  
* [Markdown Guide](https://www.markdownguide.org/)

### Authors and Acknowledgments
This "README.md" has been authored by Jahidul Islam Rahat utilizing Markdown and GitHub Pages. Special appreciation goes to Andrew Etter for his book on Technical Writing, which served as a valuable resource.
And also Thanks to all my group members for helping me .
[Shouvik roy](https://github.com/raysofhopes)
[Shadib](https://github.com/shadibhoque) 

### FAQ

**Why is Markdown better than a Word processor?**
> Markdown allows for the separation of content and style. This enables the preservation of consistency in both content and writing style without requiring constant consideration.

**Why is my resume not online?**  
> Ensure that your resume is named 'index.md.'

**How do I change a theme?**
> In your '_config.yml' file, just indicate the name of an alternative theme from this [source].(https://pages.github.com/themes/). 
