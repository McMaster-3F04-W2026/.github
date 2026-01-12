

<!--
 Block comment:
Welcome to the Github Organization for code submission for 3F04 W2026!

-->

# Submission Instructions

Welcome to the Github Organization for code submission for 3F04 W2026! To receive credit for Projects 1 and 2, you must:
1. Submit the PDF report to the Dropbox on Avenue2Learn
2. Submit your code to a private repository in this Github Organization
3. Submit the link to the repository to the autograder portal (ADD LINK HERE). The server will run your code and return your grade. 

## How to Create Your Repository

To ensure the autograder has access to your code, you **must** create your repository inside the official course organization. Follow these steps:

1. **Navigate to the Organization:** Go to `https://github.com/McMaster-3F04-W2026` 
2. **Use the Template:** - Locate the **"Project-1-Template"** repository.
   - Click the green **"Use this template"** button and select **"Create a new repository"**.
3. **Repository Settings:**
   - **Owner:** Ensure the owner is set to the Course Organization (e.g., `McMaster-3F04-W2026`).
   - **Repository Name:** Use the format `Project1-YourMacID` (e.g., `Project1-smithj99`).
   - **Visibility:** Set this to **Private**. This ensures other students cannot see your solution. Please note any public repositories may be deleted. 
4. **Create:** Click **"Create repository from template"**.

Once created, you can clone your new private repository to your local machine and begin working.

> [!CAUTION]
> If you create the repository under your personal account instead of the Organization, the autograder will not be able to see your code, and your submission will fail.

### Step 1: Push your code to GitHub
1.  **Save** your changes in `newton_raphson.m`.
2.  **Commit** your changes using the Git panel in MATLAB or the terminal:
    ```bash
    git add newton_raphson.m
    git commit -m "Implemented Newton-Raphson with relaxation"
    ```
3.  **Push** to your private repository:
    ```bash
    git push origin main
    ```

### Step 2: Register on the Autograder Portal
1.  Log in to the **3F04 Autograder Portal** using your MacID and the 8-character access code provided in Avenue2Learn in the grade item "3F04 Autograder Access Code". This access code is unique to you as for the course.
2.  Navigate to the **Submit** page.
3.  Select **"Project 1: Newton-Raphson"** from the dropdown menu.
4.  Paste your **GitHub Repository URL** (e.g., `https://github.com/McMaster-3F04-W2026/Project1-YourMacID`).
5.  Click **"Queue for Grading"**.
6.  Navigate to the **Queue** page to see where your submission is in the autograder queue. 

### Step 3: Verify your Results
1.  Go to the **My Grades** tab.
2.  Your submission will initially show as `PENDING` or `RUNNING`.
3.  Refresh after a few minutes to see your **Final Score** and the **MATLAB Console Output**.
4.  If your score is not what you expected, you may modify your code and **re-submit the code only** as many times as you like before the deadline. Your report will only be graded after the deadline has passed. Your **best code score** will be recorded. The autograder will grade a submission from each student no more frequently than every 5 minutes, in order of submission.

> [!IMPORTANT]  
> Ensure the Autograder Bot has been accepted as a collaborator on your repository, or that your repository is hosted within the official course Organization. If the bot cannot clone your code, your status will mark as `FAILED`.
