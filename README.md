# Overleaf Starter Guide

## Introduction to Overleaf
Overleaf is a cloud-based LaTeX editor that simplifies the process of writing, editing, and collaborating on LaTeX documents. While it is not a super powerful text editor, its ease of use and collaboration features make it a favorite among many users.

## Getting Started with Overleaf

### 1. Sign Up/Login
To begin using Overleaf, visit the website [Overleaf.com](https://overleaf.com) and either sign up for a new account or log in if you already have one. Use your Harvard Google account, as that will provide you with access to Overleaf’s premium subscription, and free templates.

### 2. Creating a New Project
These instructions are for projects that are hosted on GitHub, not those that just exist on Overleaf. In other words, we want you to use Overleaf as if it were an IDE for editing TeX files, not as a file storage suite as Google Docs may be. This will make it so that 1) you can collaborate with others who do not use overleaf, 2) you can keep a consistent repository space (GitHub) for all of your projects, and 3) your LaTeX files can live in the same repository as your data, etc.

To create a fully new project in Overleaf (and connecting it to GitHub):
- After logging in, you can create a new project by clicking on the "New Project" button. You'll be presented with options to start from a blank document, choose from various templates (such as research papers, presentations, CVs, etc.), or upload an existing LaTeX project.
- You can press the Overleaf project “Menu” button on the top left (next to the home symbol). 
- Then, under “Sync”, you can press “GitHub”. 
- It will pop-up with “Export Project to GitHub” and ask you to enter a repository name. When you complete the fields, press “Create a GitHub repository”
- In the future when you edit, you can commit changes with “Push Overleaf changes to GitHub"

To import an already existing project from GitHub:
- Click “Create a New Project” and then select “Import from GitHub”
- If this is your first time trying, you will have to click on the pop-up “Link to your GitHub account”
- Sign into your GitHub account when you are redirected there.
- It will redirect you back to Overleaf, and will tell you it was successfully linked.
  - You may also want to link to your Dropbox account at this screen, if you have one!
- Now, when you click “New Project”, it will show you a list of repositories that you have access to that you can import to Overleaf
- After you edit your file, and you are ready to commit it to the GitHub repository:
  - You can press the Overleaf project “Menu” button on the top left (next to the home symbol). 
  - Then, under “Sync”, you can press “GitHub”. 
  - A pop-up will appear. You can then press “Push Overleaf changes to GitHub”
  - Write your commit message & press “Commit”
    
### 3. Understanding the Overleaf Interface
Once you've created a new project, you'll see the Overleaf editor interface, which consists of:
- Text Editor: The left-hand panel where you write your LaTeX code.
- Preview Pane: The right-hand panel where you can see a live preview of your document as you write.
- Toolbar: Located at the top of the editor, it contains buttons for common actions such as compiling, saving, and sharing your document.

### 4. Writing Your Document
You can start writing your document directly in the text editor using LaTeX syntax. Here are some basic LaTeX commands to get you started:
- Document Structure: Begin with a preamble where you specify the document class, packages, and settings. The main content of your document is enclosed between \begin{document} and \end{document} tags.
- Sections and Subsections: Use commands like \section{} and \subsection{} to organize your document into sections and subsections.
- Text Formatting: Apply formatting such as bold, italics, and underline using commands like \textbf{}, \textit{}, and \underline{} respectively.
- Lists: Create itemized or numbered lists using the itemize or enumerate environments.
- Math Equations: LaTeX excels at typesetting mathematical equations. Use the $ ... $ or \[ ... \] delimiters for inline or displayed equations respectively.
- Figures and Tables: Insert figures and tables using the \includegraphics{} and table environments respectively.

### 5. Collaborating on Overleaf
One of the key features of Overleaf is its support for real-time collaboration. Here's how you can collaborate with others on a document:
- Share Project: Click on the "Share" button to invite collaborators via email. You can specify their permissions (edit or view-only) and work together in real-time on the same document.
- Version History: Overleaf keeps track of changes made to your document, allowing you to revert to previous versions if needed. You can access the version history from the history menu.
- Chat and Comments: Communicate with collaborators using the built-in chat feature or leave comments on specific parts of the document to discuss changes or provide feedback.

### 6. Exporting and Downloading
Once your document is ready, you can export it in various formats or download the source files:
- PDF Output: Overleaf automatically generates a PDF preview of your document, which you can download or share with others.
- Download Source Files: You can download the source files of your document in .zip format, including all LaTeX files, figures, and additional resources.
- Export Options: Overleaf offers export options for other formats such as Word, LaTeX, and HTML, allowing you to work with your document in different environments.

## Advanced Features and Tips
### 1. Customizing Templates
Overleaf provides a wide range of templates for different types of documents. You can also create your own custom templates or modify existing ones to suit your specific needs.

### 2. Using Bibliographies and Citations
LaTeX makes it easy to manage bibliographies and citations using tools like BibTeX or BibLaTeX. Overleaf integrates with reference management software such as Zotero, Mendeley, and EndNote, allowing you to easily insert citations and generate bibliographies.

### 3. Adding Custom Packages and Styles
If you require additional functionality or styling not provided by default in LaTeX, you can include custom packages or define your own styles in the preamble of your document.

### 4. Collaboration Best Practices
When collaborating with others on Overleaf, it's a good idea to communicate effectively, use comments and chat features for discussions, and follow version control best practices to avoid conflicts.

### 5. Learning Resources
Overleaf offers extensive documentation, tutorials, and examples to help you learn LaTeX and make the most of its features. Additionally, there are numerous online resources, forums, and communities dedicated to LaTeX where you can seek help and advice.

