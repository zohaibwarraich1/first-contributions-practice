# Contributing using GitHub Desktop

This tutorial will guide you through making your first contribution using GitHub Desktop, a user-friendly GUI application for Git.

## Prerequisites

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Create a [GitHub account](https://github.com/) if you don't have one
3. Sign in to GitHub Desktop with your GitHub account

## Step 1: Fork the Repository

1. Go to the [first-contributions-practice repository](https://github.com/iemafzalhassan/first-contributions-practice)
2. Click the **Fork** button in the top-right corner
3. This creates a copy of the repository in your GitHub account

## Step 2: Clone Your Fork

1. Open GitHub Desktop
2. Click **File** → **Clone repository**
3. Click the **GitHub.com** tab
4. Find your forked repository (`your-github-username/first-contributions-practice`)
5. Choose where to save it on your computer
6. Click **Clone**

![Clone Repository](https://docs.github.com/assets/images/help/desktop/clone-file-menu.png)

## Step 3: Create a New Branch

1. In GitHub Desktop, click **Current branch** (should show "main")
2. Click **New branch**
3. Name your branch something descriptive like `add-your-name`
4. Click **Create branch**

![Create Branch](https://docs.github.com/assets/images/help/desktop/create-branch-button.png)

## Step 4: Make Your Changes

1. Open the repository folder on your computer
2. Open `Contributors.md` in your favorite text editor
3. Add your name following the format:
   ```
   - [Your Name](https://github.com/your-github-username) - Your message here
   ```
4. Save the file

## Step 5: Review Your Changes

1. Go back to GitHub Desktop
2. You should see your changes in the left panel
3. Review the changes in the right panel to make sure they look correct
4. The changed file will be automatically selected for commit

![Review Changes](https://docs.github.com/assets/images/help/desktop/commit-all.png)

## Step 6: Commit Your Changes

1. In the bottom-left corner, add a commit message:
   - **Summary**: `Add [Your Name] to Contributors list`
   - **Description** (optional): Add any additional details
2. Click **Commit to [your-branch-name]**

![Commit Changes](https://docs.github.com/assets/images/help/desktop/commit-message.png)

## Step 7: Push Your Changes

1. Click **Push origin** to upload your changes to GitHub
2. If this is your first push, the button might say **Publish branch**

![Push Changes](https://docs.github.com/assets/images/help/desktop/push-to-origin.png)

## Step 8: Create a Pull Request

1. GitHub Desktop will show a notification about creating a pull request
2. Click **Create Pull Request** or **Preview Pull Request**
3. This will open GitHub in your web browser
4. Fill out the pull request form:
   - **Title**: Should be automatically filled
   - **Description**: Add any additional information
5. Click **Create pull request**

![Create Pull Request](https://docs.github.com/assets/images/help/pull_requests/pullrequest-send.png)

## Step 9: Wait for Review

Congratulations! You've created your first pull request. Now:

1. Wait for a maintainer to review your changes
2. They might ask for changes or approve it directly
3. Once approved, your changes will be merged into the main repository
4. You'll receive a notification when this happens

## Tips for Success

### Good Commit Messages
- ✅ "Add John Doe to Contributors list"
- ✅ "Fix typo in README.md"
- ❌ "Update"
- ❌ "Changes"

### Branch Naming
- ✅ `add-john-doe`
- ✅ `fix-readme-typo`
- ❌ `patch-1`
- ❌ `my-changes`

### Before Submitting
- Double-check your changes in GitHub Desktop
- Make sure you're on the correct branch
- Ensure your commit message is descriptive
- Test that your changes don't break anything

## Troubleshooting

### "Repository not found" error
- Make sure you've forked the repository first
- Check that you're signed in to the correct GitHub account

### Changes not showing up
- Make sure you've saved the file
- Check that you're in the correct repository folder
- Refresh GitHub Desktop (View → Refresh)

### Can't push changes
- Make sure you're connected to the internet
- Check that you have permission to push to your fork
- Try signing out and back in to GitHub Desktop

## Next Steps

After your first contribution:

1. **Explore more repositories**: Look for projects with "good first issue" labels
2. **Learn more Git**: Understanding the command line can be helpful
3. **Join communities**: Participate in open source communities
4. **Keep contributing**: The more you contribute, the more you'll learn!

## Additional Resources

- [GitHub Desktop Documentation](https://docs.github.com/en/desktop)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Open Source Guide](https://opensource.guide/)

Happy contributing! 🎉