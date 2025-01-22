# Git and Github health check
## ** Create and Edit a File**
**Objective:** Practice creating, editing, committing, and pushing changes to the repository.

1. **Step 1: Instructions (in GitHub README):**
   - Clone this repository to your local machine using:
     

bash
     git clone <repository-url>


   - Navigate into the repository folder using git bash:
     

bash
     cd <repository-name>


   - Create a new file named introduction.txt:
     

bash
     touch introduction.txt


   - Open the file in a text editor (e.g., nano, vim, or a graphical editor) and write:
     

My name is [Your Name], and I'm learning Git!


   - Save the file.
   - Stage the file for commit:
     

bash
     git add introduction.txt


   - Commit your changes with a meaningful message:
     

bash
     git commit -m "Add introduction file"


   - Push your changes to the remote repository:
     

bash
     git push



---

### **Step 2: Update a File**
**Objective:** Practice pulling the latest changes, editing a file, and committing updates.

1. **Instructions (in GitHub README):**
   - Make sure your local repository is up to date:
     

bash
     git pull


   - Open the introduction.txt file you created earlier and add a new line:
     

My favorite programming language is [Your Favorite Language].


   - Save the file.
   - Check the status of your repository to confirm the file was modified:
     

bash
     git status


   - Stage and commit your changes with a descriptive message:
     

bash
     git add introduction.txt
     git commit -m "Update introduction with favorite programming language"


   - Push your changes to the remote repository:
     

bash
     git push





# CSS-Introduction
This repo will be used for web development lab #3, which validates basic CSS knowledge for students

## Repo structure:

This repo consist of 4 directories, in each directory you wil find 2 files per the following structure:<br />
```
├── Poster
│   ├── assets/images/daenerys.jpg
│   ├── goal.png
│   ├── style.css
│   └── index.html
├── Colors
│   ├── goal.png
│   ├── assets/images/
│   └── index.html ** has instructions **
├── Fonts
│   ├── goal.png
│   ├── font-size.html
│   ├── font-family.html
│   └── index.html
└── Selectors
    ├── goal.png
    ├── style.css
    └── index.html
```
## Instructions:
1. Clone the repository on your local machine.
2. Edit the <code>index.html</code>  and <code>style.css</code>  files,  make the necessary modifications to match the <code>goal.png</code> on each folder, some folders have comments with additional instructions or hints.
3. Commit your changes and push them to the github repository.
4. Create a pull request for review.
5. Once all students complete the Pull Request or the time assigned from the teacher is completed, an issue in your github repository will be created.
6. Follow the instructions of the github issue.

## Evaluation criteria

|  **Percentage**       |**Directory**       | **Criteria**                                   | **YES**       | **NO**        | **Observations** |
|------------------------------------------|------------------------------------------|-----------------------------------------------|-------------------------------|--------------------------|--------------------------|
|  **25%**  |**Poster**  | Matches the png image?   |    |          |       |
| **25%**  |**Colors** | Matches the png image?               |        |   |    |
| **25%**  |**Fonts**      | Matches the png image?       |        | |  |
| **25%**  |**Selectors** | Matches the png image?         |    |    | |
