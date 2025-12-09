# ForgeEd - Project Presentation Website

A static presentation website for **ForgeEd - AI-Enhanced Learning Management System**, a 16-week Master's Research Project at Saint Louis University.

## Live Links

- **Presentation Website**: [View on GitHub Pages](https://YOUR_USERNAME.github.io/forgeed-presentation/)
- **Live Application**: [https://forgeed.replit.app/](https://forgeed.replit.app/)
- **Source Code**: [https://github.com/pavankumars97531/forgeed](https://github.com/pavankumars97531/forgeed)

## Project Overview

ForgeEd is a unified, AI-enhanced Learning Management System designed to support students holistically across academics, wellbeing, and career development. This presentation website showcases:

- Executive Summary
- Problem Context & Research
- Proposed Solution & Features
- System Architecture
- Database Design (ER Diagram)
- Core Features
- Team Information

## How to Host on GitHub Pages

Follow these steps to host this website on GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** button in the top right corner and select **New repository**
3. Name your repository (e.g., `forgeed-presentation`)
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload the Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click **uploading an existing file**
2. Drag and drop these files/folders:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `assets/` folder (contains images)
3. Add a commit message (e.g., "Initial upload of presentation website")
4. Click **Commit changes**

**Option B: Using Git Command Line**

```bash
# Clone your new repository
git clone https://github.com/YOUR_USERNAME/forgeed-presentation.git

# Copy the website files into the cloned folder
# Then commit and push
cd forgeed-presentation
git add .
git commit -m "Initial upload of presentation website"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon in the top menu)
3. In the left sidebar, click **Pages**
4. Under **Source**, select:
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

1. Wait 1-2 minutes for GitHub to build your site
2. Your website will be available at:
   ```
   https://YOUR_USERNAME.github.io/forgeed-presentation/
   ```
3. The URL will appear in the Pages settings once it's ready

## File Structure

```
forgeed-presentation/
├── index.html          # Main HTML file with all content sections
├── styles.css          # CSS styles with ForgeEd brand colors
├── script.js           # JavaScript for navigation and animations
├── README.md           # This file
└── assets/
    └── images/
        ├── logo.png           # ForgeEd logo
        ├── team.jpeg          # Team photo
        ├── architecture.png   # System architecture diagram
        └── er-diagram.png     # Database ER diagram
```

## Website Sections

1. **Home** - Hero section with logo, project title, and links
2. **Executive Summary** - Project overview and key features
3. **Problem Context** - Research findings and stakeholder analysis
4. **Proposed Solution** - Core modules and project charter
5. **Architecture** - System architecture diagram and tech stack
6. **Database Design** - ER diagram and data entity descriptions
7. **Core Features** - Academic, AI-powered, and admin features
8. **Team** - Team photo, member names, and lessons learned

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- Vanilla JavaScript
- Google Fonts (Inter)
- Font Awesome Icons

## Team ForgeEd

- Ullas Giddegowda Gowda
- Pavan Kumar Suresh
- Pranay Reddy Shashidhar Reddy
- Ruthvik Ajit Chiniwal
- Harshith Shivaswamy

## Troubleshooting GitHub Pages

**Website not showing up?**
- Wait a few minutes - initial deployment can take 2-5 minutes
- Check Settings > Pages for any error messages
- Ensure `index.html` is in the root directory

**Images not loading?**
- Verify the `assets/images/` folder was uploaded
- Check that image file names match exactly (case-sensitive)

**404 Error?**
- Make sure the repository is public
- Confirm GitHub Pages is enabled in Settings > Pages
- Check the correct branch is selected

## License

This presentation website is part of the ForgeEd academic project at Saint Louis University.
