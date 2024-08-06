
You can create this file in your local repository directory by running:

```bash
echo "# PLPBasicGitAssignment

## Task 1: Repository Setup

### 1. GitHub Repository Creation:
- Log in to your GitHub account.
- Create a new repository on GitHub named \"PLPBasicGitAssignment\".
- Initialize the repository with a README file.(tick the checkbox down the page)

## Task 2: Local Setup

### 2. Local Folder Setup:
- Create a new folder on your local machine(This PC) named \"PLPBasicGitAssignment\".
- Open a terminal or command prompt and navigate to the created folder.(right click in the folder then choose what to open with)

### 3. Git Initialization:
- Initialize a new Git repository in your local folder by running the following command:
  \`\`\`bash
  git init
  \`\`\`

### 4. Connecting to GitHub:
- Link your local repository to the GitHub repository you created in Task 1 by running the following command:
  \`\`\`bash
  git remote add origin <repository-url>
  \`\`\`
  Replace \`<repository-url>\` with the actual URL of your GitHub repository.

## Task 3: Making Changes

### 5. Create a File:
- Inside your local folder, create a new text file named \`hello.txt\`.
- Add a simple text message to the file:
  \`\`\`bash
  echo \"Hello, Git!\" > hello.txt
  \`\`\`

### 6. Committing Changes:
- Stage the changes by running the following command:
  \`\`\`bash
  git add hello.txt
  \`\`\`
- Commit the changes by running the following command:
  \`\`\`bash
  git commit -m \"Add hello.txt with a greeting\"
  \`\`\`

## Task 4: Pushing to GitHub

### 7. Pushing to GitHub:
- Push the committed changes to your GitHub repository by running the following command:
  \`\`\`bash
  git push --set-upstream origin master
  \`\`\`
- I had challenges between the two branches I have on this account therefore I opted to use my local branch 'master' to avoid the conflicts being created between ranch'master' and 'main'.

  

## Task 5: Verification

### 8. Verify on GitHub:
- Visit your GitHub repository in a web browser and confirm that the \`hello.txt\` file and commit message are visible.
- Then submit assignment
