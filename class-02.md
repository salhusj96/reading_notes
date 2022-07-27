# **Class 02 Reading Notes**

## **GitHub**
- *Why does this topic matter?*
  - GitHub is going to be the primary medium through which we will be submitting our working assignments as well as our Ops challenges, so it is imperative that we as students understand the basics of how GitHub functions and how to best use it for our needs. It is also used very often in the Ops industry.
---
### **Getting started with GitHub**
- GitHub is a code hosting platform for version control and collaboration.
#### **Git Hub Essentials**
  - Repositories
  - Branches
  - Changes and commits
  - Pull requests  
#### **Creating a Repository**
  - Used to organize a single project
  - Contains folders, files, images, videos, etc.
  - Often includes a README.md file
    - README files are written in Markdown language
  - GitHub also offers a license file

1. In the upper-right corner of any page, use the + drop-down menu, and select **New repository**
2. In the **Repository name** box, enter the repository name.
3. In the **Description** box, write a short description of the repository.
4. Select **Add a README file**
5. Select whether your repository will be **Public** or ***Private**
6. Click **Create Repository** (*Big green button*)

#### **Committing a change**
- a commit functions as a snapshot of all files in project at a particular point in time

1. `git add filename` to update what will be committed to the repo
2. `git commit -m "descriptor of change"` to commit the change to the file
3. `git push origin main` to direct the change to the repository 
   
#### **Branches**
- Branches allow for different versions of a repo at one time
- Repo has one branch named `main` by default
- Can create additional branch-offs from `main` in your repository
- can utilizes branches to make edits/experiments before committing them to `main`

#### **Pull Requests**
- The heart of collaboration on GitHub
- Proposes changes and requests review to pull in contributions to be merged into a branch
- Pull requests show diffs (differences) of the content from both branches
- Changes are shown via additions (+) and subtractions (-) in different colors

---

## **VS Code**
- *Why does this topic matter?*
  - VS Code is the primary editor we will be using to create and edit our code for assignment submissions in this class, and it is important that we know how to work inside of it as it is considered the industry standard for almost everything that has to do with code.
---
### **Setup**
- VS code is a free code editor, runs on;
  - macOS
  - Linux
  - Windows
- Windows Installation
  1. Download the installer (.exe)
  2. Run the installer
  3. Will be installed under `C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code`
- User Setup
  - Does not require admin privileges
  - Located in `LOCAL AppData` folder
  - Provides a smoother background update experience
- System Setup
  - Requires Admin privileges
  - Places the installation under `/Program Files/`
  - Available to all users on the system
### **Getting Started**
- The **Get Started** page gives an overview of VS Code's customizations and features
- Gives the option to pick a **Walkthrough** for a self-guided tour through setup steps, features, and customizations
- Can also use the **Interactive Editor Playground** to improve code editing skills using features like;
  - Intellisense
  - Snippets
  - Emmet
  - Multi-cursor editing
- Command Palette
  - `CTRL+Shift+P`
  - Accesses all available commands based on current context
- Default keyboard shortcuts
![Keyboard shortcuts](https://code.visualstudio.com/assets/docs/getstarted/tips-and-tricks/keyboard-references.png)
- Keyboard Reference Sheet
![Keyboard reference sheet](https://code.visualstudio.com/assets/docs/getstarted/tips-and-tricks/KeyboardReferenceSheet.png)
- Quick Open (quickly opens files)
  - `Ctrl+P`


### **Terminal Basics**
- **Ctrl+`** to open the terminal
- can use various shells installed on your machine
  - PowerShell on Windows (Default)
  - Command Prompt on Windows (Default)
---
## **Summary**
- GitHub is a powerful tool used by coders and programmers to upload and share their coding projects with others in collaboration. Collaboration is the modus operandi of GitHub and serves as its primary purpose, to making sharing your code with others easy.
  - For an analogy, GitHub is kind of like a whiteboard for internet coders. One person can wrte something down with a marker, and others can contribute by changing what was written or writing onto their own sections of the whiteboard.
- VS Code is another powerful tool for coders that allows them to create and edit code and allows for several different types of plugins to support a myriad of projects being developed in all different kinds of programming languages, such as Python, C/C++, and many others.
  - VS Code is a lot like the Rosetta Stone of coding, where the original Rosetta Stone was used by scholars to help decipher ancient Egyptian hieroglyphs, VS Code functions in a similar way to help you decipher and create code starting with the basics and expanding into additional languages.

## Things I want to know more about
- Practical uses of other programming languages, specifically in CyberOps 
- Python; everything there is to know