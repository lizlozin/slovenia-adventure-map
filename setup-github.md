# GitHub Setup Instructions

## Step 1: Create Repository on GitHub

1. Go to https://github.com and sign in
2. Click the "+" icon → "New repository"
3. Repository name: `slovenia-adventure-map`
4. Description: `Interactive itinerary map for a 13-day Slovenia adventure`
5. Make it **Public** (required for free GitHub Pages)
6. **DO NOT** check "Add a README file" (we already have one)
7. Click "Create repository"

## Step 2: Connect Local Repository to GitHub

After creating the repository, run these commands in your terminal:

```bash
# Navigate to your project directory (if not already there)
cd /Users/lizloz/slovenia-adventure-map

# Add the GitHub repository as remote origin
# Replace 'yourusername' with your actual GitHub username
git remote add origin https://github.com/yourusername/slovenia-adventure-map.git

# Rename the default branch to main (if needed)
git branch -M main

# Push your code to GitHub
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

## Step 4: Access Your Live Site

After enabling GitHub Pages, your site will be available at:
`https://yourusername.github.io/slovenia-adventure-map`

It may take a few minutes for the site to become available.

---

**Note**: Replace 'yourusername' with your actual GitHub username in all URLs and commands above.
