# 🚀 Deploy Your Portfolio to GitHub Pages

Your portfolio is now ready to deploy! Follow these steps:

## Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Choose a repository name:
   - For personal site: `nileshtheekshana.github.io`
   - Or any name like: `portfolio`
5. Keep it **Public**
6. **DO NOT** initialize with README (you already have one)
7. Click **"Create repository"**

## Step 2: Push Your Code to GitHub

Copy and run these commands in your terminal:

```bash
cd /home/nilesh/Desktop/portfolio

# Add your GitHub repository as remote
git remote add origin https://github.com/nileshtheekshana/YOUR_REPO_NAME.git

# Push your code
git push -u origin main
```

Replace `YOUR_REPO_NAME` with the actual repository name you created.

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down and click **Pages** (left sidebar)
4. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**

## Step 4: Access Your Live Site

After 1-2 minutes, your site will be live at:

- **Personal site**: `https://nileshtheekshana.github.io/`
- **Project site**: `https://nileshtheekshana.github.io/YOUR_REPO_NAME/`

## 🔄 Update Your Portfolio Later

Whenever you make changes:

```bash
cd /home/nilesh/Desktop/portfolio
git add .
git commit -m "Update portfolio"
git push
```

Your site will automatically update within 1-2 minutes!

## ✅ Current Status

- ✅ Git repository initialized
- ✅ All files committed
- ✅ Ready to push to GitHub

## 📝 Quick Commands Reference

```bash
# Check repository status
git status

# See commit history
git log --oneline

# View remote repository
git remote -v
```

---

**Need help?** Check the [GitHub Pages Documentation](https://docs.github.com/en/pages)
