# 🚀 GitHub Profile Setup Guide

## Step 1: Create Your Profile Repository

1. Go to GitHub and create a **new repository**
2. Name it **exactly** as your GitHub username (e.g., if your username is `john-doe`, name the repo `john-doe`)
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

## Step 2: Upload Your Files

1. Upload `README.md` to the root of your repository
2. Upload `avatar.png` (your profile picture) to the root
3. Create a `.github/workflows` folder in your repository
4. Upload `snake.yml` to `.github/workflows/`

## Step 3: Customize Your Profile

Open `README.md` and replace the following placeholders:

### Required Changes:
- `YOUR_USERNAME` - Replace with your GitHub username (appears multiple times)
- `YOUR_NAME` - Replace with your full name
- `[YOUR NAME]` - Replace in the typing animation section

### Optional Changes:
- Update the `developer` object with your actual information:
  - Programming languages you use
  - Technologies and frameworks
  - Location (currently set to "Kigali, Rwanda")
  - Current focus/projects
  
### Social Media Links:
Replace these with your actual profiles (or remove sections you don't use):
- `YOUR_LINKEDIN` - LinkedIn profile username
- `YOUR_TWITTER` - Twitter handle
- `YOUR_SPOTIFY_ID` - Spotify user ID (optional, see below)
- Email address

## Step 4: Enable GitHub Actions (for Snake Animation)

1. Go to your repository **Settings**
2. Click on **Actions** in the left sidebar
3. Under "Actions permissions", select **"Allow all actions and reusable workflows"**
4. Click **Save**

## Step 5: Trigger the Snake Animation

1. Go to the **Actions** tab in your repository
2. Click on "Generate Snake Animation" workflow
3. Click **"Run workflow"** → **"Run workflow"**
4. Wait a few minutes for it to complete
5. The snake animation will appear on your profile!

## 📝 Additional Customizations

### Change the Color Theme
The profile uses the `tokyonight` theme. You can change it to:
- `radical`
- `merko`
- `gruvbox`
- `dark`
- `dracula`
- `monokai`

Just replace `theme=tokyonight` with your preferred theme in the README.

### Get Your Spotify ID (Optional)
1. Go to https://open.spotify.com/
2. Click on your profile
3. Click "Share" → "Copy link to profile"
4. Extract the ID from the URL: `https://open.spotify.com/user/YOUR_SPOTIFY_ID`

### Update Tech Stack Icons
Edit the skillicons URL to add/remove technologies:
```
https://skillicons.dev/icons?i=js,ts,react,nodejs,python
```

Available icons: https://skillicons.dev

## 🎨 Features Included

✅ Animated typing header
✅ Profile view counter
✅ GitHub stats with dark theme
✅ Streak stats
✅ Most used languages
✅ Trophy collection
✅ Contribution graph
✅ Snake eating contributions animation
✅ Random dev quote
✅ Spotify integration (optional)
✅ Social media badges
✅ Custom tech stack showcase

## 🔧 Troubleshooting

### Snake animation not showing?
- Make sure GitHub Actions is enabled in your repository settings
- Check if the workflow ran successfully in the Actions tab
- Wait up to 10 minutes for the first generation

### Stats not loading?
- Check that your username is spelled correctly
- Make sure your repository is public
- GitHub APIs sometimes have rate limits - wait a few minutes and refresh

### Want to update your profile?
- Just edit the README.md file directly on GitHub
- Changes will be visible immediately

## 📚 Resources

- [GitHub README Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [Skill Icons](https://github.com/tandpfun/skill-icons)
- [Shields.io Badges](https://shields.io/)

---

**Need help?** Check out the GitHub repository for each widget linked in the Resources section above!
