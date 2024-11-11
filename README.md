# CSESDocumentProject

This is a repository for the CSES Technical Workshop Document Project. We will be making a file document organization web application, learning from CSES as we go. 
This project is a group project, worked on by Phillip, William, Anisha, and Mahdi.

### Setting Up the Environment

**Note**: You may have to restart terminal after installing each environment.

#### Downloading Git (and Git Bash)

1. Download git and git bash by following [this link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
2. Set up Git Bash as the shell for running command line prompts (in VSCode or directly openning Git Bash)
3. Run:
   ```bash
   git -v
   ```
   This should output something like this:
   ```bash
   git version 2.46.0.windows.1
   ```

#### Downloading Node.JS

1. Download **nvm (Node Version Manager)**. Follow the instructions on in [this link](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/) for the details.
2. Run:
   ```bash
   nvm -v
   ```
   This should output the version of nvm you installed.
3. Install **Node.js v18.20.4**:
   ```bash
   nvm install v18.20.4
   ```
4. Switch to the installed version:
   ```bash
   nvm use v18.20.4
   ```
5. Run:
   ```bash
   node -v
   npm -v
   ```
   The results should be something like:
   ```bash
   v18.20.4
   10.7.0
   ```

### Setting Up the Local Repository

1. **Fork the repository** to your GitHub account.
2. **Clone** the origin repository locally:
   ```bash
   git clone https://github.com/Phil5184/CSESDocumentProject.git
   ```
3. Create a **remote repository**:
   ```bash
   git remote add [your-username] https://github.com/[your-username]/CSESDocumentProject.git
   ```
4. Run:
   ```bash
   git remote -v
   ```
   The output should be something like the following:
   ```bash
   [your-username]    https://github.com/[your-username]/CSESDocumentProject.git (fetch)
   [your-username]    https://github.com/[your-username]/CSESDocumentProject.git (push)
   origin  https://github.com/Phil5184/CSESDocumentProject.git (fetch)
   origin  https://github.com/Phil5184/CSESDocumentProject.git (push)
   ```

### Running your new project locally
In your terminal, switch to your new Angular project.
```bash
cd document-uploader
```

All of your dependencies should be installed at this point (which you can verify by checking for the existent for a node_modules folder in your project), so you can start your project by running the command:
```bash
npm start
```

If everything is successful, you should see a similar confirmation message in your terminal:

``` bash
Watch mode enabled. Watching for file changes...
NOTE: Raw file sizes do not reflect development server per-request transformations.
 ➜ Local: http://localhost:4200/
 ➜ press h + enter to show help
```

And now you can visit the path in Local (e.g., http://localhost:4200) to see your application. Happy coding! 🎉

### Development Guidlines

#### Code Style

Please follow these coding style guidelines:

- We recommend using Prettier to format on save, and then running ESLint before making a pull request.
- Indent with tabs and use a 2-space indentation.
- Use semicolons and the end of each line.
- Write clear, concise comments where necessary.
- Use meaningful variable and function names.

### Commit Messages

Please write a rough description for the changes made in each commits
