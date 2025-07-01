# Git Basics for Beginners

This guide covers the essential Git commands you'll need to make your first contribution.

## What is Git?

Git is a version control system that helps you track changes in your code and collaborate with others. Think of it as a way to save different versions of your work and merge changes from multiple people.

## Essential Git Commands

### 1. Clone a Repository
```bash
git clone https://github.com/iemafzalhassan/first-contributions-practice.git
```
This downloads a copy of the repository to your local machine.

### 2. Check Status
```bash
git status
```
Shows you which files have been modified, added, or deleted.

### 3. Create a New Branch
```bash
git switch -c <branch-name>
# or for older Git versions:
git checkout -b <branch-name>
```
Creates a new branch for your changes. Always work on a separate branch!

### 4. Add Changes
```bash
git add <filename>
# or to add all changes:
git add .
```
Stages your changes for commit.

### 5. Commit Changes
```bash
git commit -m "Your commit message"
```
Saves your changes with a descriptive message.

### 6. Push Changes
```bash
git push origin <branch-name>
```
Uploads your changes to GitHub.

## Best Practices

### Commit Messages
- Use clear, descriptive messages
- Start with a verb (Add, Fix, Update, etc.)
- Keep it under 50 characters for the first line
- Example: "Add John Doe to Contributors list"

### Branch Names
- Use descriptive names
- Use hyphens to separate words
- Examples: `add-john-doe`, `fix-typo-readme`, `update-contributing-guide`

### Before You Commit
- Always check `git status` to see what you're committing
- Review your changes with `git diff`
- Make sure you're on the right branch

## Common Git Workflow

1. **Fork** the repository on GitHub
2. **Clone** your fork to your local machine
3. **Create** a new branch for your changes
4. **Make** your changes
5. **Add** and **commit** your changes
6. **Push** your branch to your fork
7. **Create** a pull request on GitHub

## Troubleshooting

### "Git command not found"
You need to install Git first. Visit [git-scm.com](https://git-scm.com/) to download it.

### "Permission denied (publickey)"
You need to set up SSH keys. Follow [GitHub's SSH guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

### "Your branch is behind 'origin/main'"
```bash
git pull origin main
```
This updates your local branch with the latest changes.

### Accidentally committed to main branch
```bash
git switch -c new-branch-name
git switch main
git reset --hard origin/main
```
This moves your changes to a new branch and resets main.

## Next Steps

Once you're comfortable with these basics:
- Learn about merge conflicts and how to resolve them
- Explore Git GUI tools like GitHub Desktop
- Practice with more complex Git workflows
- Contribute to more open source projects!

## Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub's Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Interactive Git Tutorial](https://learngitbranching.js.org/)
- [Pro Git Book (Free)](https://git-scm.com/book)

Happy coding! 🚀