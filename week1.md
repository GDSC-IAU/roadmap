**1. Setup:**

   - **Set up Git:**
     - Download and install Git from the official website: https://git-scm.com/downloads.
     - Open your terminal or command prompt.
     - Configure Git with your name and email address:
       ```
       git config --global user.name "Your Name"
       git config --global user.email "your@email.com"
       ```

   - **Create a GitHub Account:**
     - Go to https://github.com/ and sign up for a free GitHub account.

   - **Create a GitHub Repository:**
     - Log in to your GitHub account.
     - Click on the '+' sign in the upper right corner and select "New Repository."
     - Follow the on-screen instructions to create a new repository. Name it "SimpleWebsite."

**2. Initial Commit:**

   - **Create a Folder:**
     - Create a folder on your local machine where you want to store your project.

   - **Create an HTML File:**
     - Inside the project folder, create an HTML file (e.g., `index.html`) using a text editor or code editor of your choice.
     - Add some basic HTML content to the file.

   - **Initialize a Git Repository:**
     - Open your terminal or command prompt.
     - Navigate to your project folder using the `cd` command.
     - Initialize a Git repository in the project folder:
       ```
       git init
       ```

   - **Add and Commit:**
     - Add the HTML file to the Git repository:
       ```
       git add index.html
       ```
     - Commit the changes with a meaningful message:
       ```
       git commit -m "Initial commit"
       ```

**3. Branching:**

   - **Create a New Branch:**
     - Create a new branch named "feature":
       ```
       git branch feature
       ```

   - **Switch to the New Branch:**
     - Switch to the "feature" branch:
       ```
       git checkout feature
       ```

   - **Make Changes:**
     - Make changes to the `index.html` file in the "feature" branch using a text editor.

**4. Merging:**

   - **Switch Back to Main:**
     - Switch back to the main branch:
       ```
       git checkout main
       ```

   - **Merge the Branch:**
     - Merge the "feature" branch into the main branch:
       ```
       git merge feature
       ```

**5. Remote Repository:**

   - **Link to GitHub:**
     - Link your local repository to the GitHub repository you created earlier. Replace `<repository URL>` with the URL of your GitHub repository:
       ```
       git remote add origin <repository URL>
       ```

   - **Push to GitHub:**
     - Push your local repository to GitHub:
       ```
       git push -u origin main
       ```

**6. Pull Requests:**

   - **GitHub Pull Request:**
     - Go to your GitHub repository in a web browser.
     - Click on the "Pull Requests" tab.
     - Click the "New Pull Request" button.
     - Select "main" as the base branch and "feature" as the compare branch.
     - Add a description for the Pull Request.
     - Review the changes and create the Pull Request.

**7. Collaboration (Optional):**

   - **Invite Collaborators:**
     - In your GitHub repository, go to "Settings."
     - Click on "Collaborators" on the left sidebar.
     - Invite a friend by entering their GitHub username or email address.

   - **Collaborate:**
     - Your friend can clone the repository to their local machine using `git clone <repository URL>`.
     - They can create a branch, make changes, commit, and push to GitHub.
     - Your friend can then create a Pull Request in the same way as described in step 6.