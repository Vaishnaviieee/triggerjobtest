This repo is for testing purpose. 
We are executing this branch through jenkins pipeline
## Setting Up a Jenkins Job to Clone a Git Repository

Follow these steps to set up a Jenkins job that clones a Git repository and builds it:

1. **Open Jenkins Dashboard**:
   - Navigate to your Jenkins dashboard.

2. **Create a New Job**:
   - Click on `New Item`.
   - Enter a name for your job.
   - Select `Freestyle project`.
   - Click `OK`.

3. **Configure the Job**:
   - In the job configuration page, go to the `Source Code Management` section.
   - Select `Git`.
   - Enter the repository URL: `https://github.com/YourUsername/YourRepo.git`.

4. **Define the Branch**:
   - In the `Branches to build` field, specify the branch you want to pull (e.g., `main` or `master`).
   
5. **Save the Configuration**:
   - Click `Save` to save the job configuration.

6. **Ensure Git is Installed on the Jenkins Server**:
   - Verify that Git is installed and properly configured on your Jenkins server.
   - You can do this by running `git --version` on the server's command line.

7. **Build the Job**:
   - On the Jenkins dashboard, select your job.
   - Click `Build Now` to trigger a build.

8. **View Workspace**:
   - Once the build is complete, go to the job page.
   - Click on `Workspace` to see the repository files and contents.

