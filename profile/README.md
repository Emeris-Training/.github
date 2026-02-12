# 🎓 Student Guide: Setting Up & Using GitHub Desktop

Welcome to your training repository! This guide provides a step-by-step walkthrough to accept your assignment, clone the repository, and manage your project files using GitHub Desktop.

---

## ⚠️ Important: Your GitHub Profile
**Please read this before creating your account or accepting the assignment.**

* **Account Ownership:** This GitHub account is **managed by you**, not the college. You are responsible for remembering your password and keeping it secure.
* **Email Address:** Please sign up using your **`@myemeris`** email address to ensure you are correctly linked to our classroom roster.
* **Professionalism Matters:** Choose a **professional username** (e.g., `JSmith-Dev` or `JaneDoe`). Avoid inappropriate nicknames or slang.
* **Your Portfolio:** This profile will exist after you leave school. It will serve as your **professional portfolio** that future employers will look at to see your code history and coding habits. Make it count!

---

## 🛠 Prerequisites

Before starting, ensure you have the following installed and set up:
1.  **GitHub Account:** Make sure you are logged into [GitHub.com](https://github.com).
2.  **GitHub Desktop:** Download and install [GitHub Desktop](https://desktop.github.com/).

### 🔑 Vital Step: Sign In to GitHub Desktop
**Do this before proceeding!**
1.  Open the **GitHub Desktop** application on your computer.
2.  Go to **File** > **Options** (Windows) or **GitHub Desktop** > **Settings** (Mac).
3.  Select **Accounts**.
4.  Click **Sign In** under the "GitHub.com" section.
5.  Use the details you just created for your GitHub account.

---

## 🚀 Part 1: Setting Up Your Repo

### Phase 1: Accept the Assignment
1.  Click the **GitHub Classroom link** provided by your lecturer.
2.  Select your name from the identifier list (if prompted) to link your GitHub account.
3.  Click **"Accept this assignment"**.
4.  Wait a moment for GitHub to configure your repository. Once complete, click the link provided to view your new personal repository.

    > **📧 Important One-Time Check:** > If you click the link and get an error, or if the repository doesn't generate immediately, **check your email inbox**.  
    > GitHub sometimes requires you to accept an invitation to join the organization first. Look for an invite link in the email address you used to sign up for GitHub. This is a one-time event; once you accept the invite, you can try the link again.

### Phase 2: Clone the Repository
Now that your repository exists on the cloud, you need to get a copy on your computer. You can do this in one of two ways:

**Option A: The "Set up in Desktop" Button (Easiest for New Repos)**
If your repository is completely empty, you will see a big setup box on the screen.
1.  Look for the button that says **"Set up in Desktop"**.
2.  Click it to automatically launch GitHub Desktop.
3.  Proceed to step 4 below.

**Option B: The Green "Code" Button (Standard Method)**
If you don't see the setup button:
1.  Look for the green **Code** button near the top right of the file list.
2.  Select **"Open with GitHub Desktop"**.
3.  Proceed to step 4 below.

**Finalizing the Clone (For both options):**

4.  When prompted, allow the browser to open GitHub Desktop.
5.  In GitHub Desktop, a "Clone a Repository" window will appear.
    * **Local Path:** Choose where you want to save this folder on your computer (e.g., your `Documents` or `Dev` folder).
    * **Important:** Remember this location!
6.  Click **Clone**.

You now have a linked folder on your computer!

### Phase 3: Add Your Project Files
Choose the scenario that matches your situation:

**Scenario A: You already have project files (Moving existing files)**
1.  Open the folder where your existing project files are located.
2.  Select all your files and **Cut** them (Ctrl+X or Cmd+X).
3.  Navigate to the **new folder** created by GitHub Desktop in Phase 2.
4.  **Paste** the files inside this new folder (Ctrl+V or Cmd+V).

**Scenario B: You are starting from scratch**
1.  Open your IDE (Visual Studio, VS Code, etc.).
2.  Select **Create New Project**.
3.  When asked for the **Location**, browse to and select the folder created by GitHub Desktop in Phase 2.
4.  Create your project directly inside that folder.

### Phase 4: Commit and Push (Crucial Step!)
Moving files into the folder is not enough. You must manually tell GitHub to save these changes to the cloud.

1.  Open **GitHub Desktop**.
2.  You should see a list of your new files on the left side with green `+` icons.
3.  **Summary Field:** In the bottom left box, write a short title for your update (e.g., "Initial project upload").
4.  **Commit:** Click the blue **Commit to master** button.
5.  **Push:** Look at the top toolbar. Click **Push origin** to send your code to GitHub.

**Verification:** Go back to your repository webpage and refresh. You should now see your files listed there.

---

## 🧠 Part 2: The Core Commands (Cheat Sheet)

You will hear these terms constantly. Here is what they actually mean.



### 1. Fetch vs. Pull (Downloading)
When you work on a team (or multiple computers), code changes happen on the server. You need to get them.

* **Fetch:** This is like looking into your mailbox to see *if* you have mail. It doesn't put the mail on your desk yet; it just tells you "Hey, there are changes on the server."
* **Pull:** This takes the mail out of the box and dumps it on your desk. It downloads the changes from the server and updates your files immediately.
    * *Rule of thumb:* Always **Pull** before you start coding for the day!

### 2. Commit (Saving)
* **Commit:** This is a local checkpoint. It saves your changes to your computer's history, but **not** to the internet yet. You can commit 100 times without the internet knowing.

### 3. Push (Uploading)
* **Push:** This sends all your "Commits" up to the GitHub cloud. Until you Push, your lecturer cannot see your work, and your code is not backed up.

---

## 🛠 Part 3: Tools & Ways of Working

You might notice that your code editor (Visual Studio, VS Code, IntelliJ) also has buttons that say "Git", "Commit", or "Sync".

**"Can I use my IDE instead of GitHub Desktop?"**
**Yes, absolutely.**

Once you have your repository set up and running, you are free to use the built-in Git tools inside your IDE. Many developers prefer this because they don't have to switch windows.

**"So why use GitHub Desktop?"**
We use GitHub Desktop in this training because it is a **visual teaching tool**.
* It clearly shows you exactly which files changed.
* It visually separates the "coding" from the "saving".
* It teaches you the specific steps (Stage -> Commit -> Push) without hiding them behind a single magic button.

Once you master the concepts here, feel free to use whatever tool fits your workflow best!

---

## 🌍 Real-World Scenarios: Why We Use Git

Here are a few superpowers you now have by using GitHub.

### 1. The "Work from Anywhere" Workflow (New PC / Lab Computer)
Did you buy a new laptop? Or do you need to work on a Lab Computer today and your Laptop tomorrow?
1.  **On PC #1:** Ensure you have **Pushed** your latest changes to the cloud.
2.  **On PC #2:** Open GitHub Desktop.
3.  Go to **File** > **Clone Repository**.
4.  Select your repo and clone it.
5.  **Result:** All your work is exactly where you left it.

**Note:** When you switch back to PC #1, don't forget to click **Fetch/Pull** in the toolbar to download the work you did on PC #2!

### 2. The "Time Machine" (Undo Button)
Did you delete a critical chunk of code by accident? Or did you write code that completely broke your app?
1.  Open GitHub Desktop and click the **History** tab.
2.  Find the commit *before* you made the mistake.
3.  Right-click that commit and select **Revert changes in commit**.
4.  Git will automatically undo the bad code for you.

### 3. The Ultimate Backup
If your hard drive crashes or your laptop gets stolen, your project is safe. Because you **Pushed** your code to GitHub, you can simply log into any other computer, clone your repo, and you are back in business immediately.
