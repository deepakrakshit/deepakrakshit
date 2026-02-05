🚀 Advanced GitHub Profile README - Setup Guide
📋 Prerequisites
A GitHub account
Repository named exactly as your username (e.g., deepakrakshit/deepakrakshit)
Repository must be public
🔧 Setup Instructions
Step 1: Create Your Profile Repository
Go to GitHub and create a new repository
Name it exactly as your GitHub username: deepakrakshit
Make it public
Initialize with a README (you'll replace this)
Step 2: Upload the Files
Upload these files to your repository:
README.md - The main profile README
.github/workflows/snake.yml - GitHub Actions workflow for snake animation
Step 3: Enable GitHub Actions
Go to your repository Settings
Navigate to Actions → General
Under Workflow permissions, select:
✅ Read and write permissions
✅ Allow GitHub Actions to create and approve pull requests
Click Save
Step 4: Activate the Snake Animation
Go to Actions tab in your repository
Click on Generate Snake Animation workflow
Click Run workflow → Run workflow
Wait for the workflow to complete (~1 minute)
The snake will appear on your profile!
Step 5: Customize (Optional)
Update Personal Information
Edit README.md and customize:
Your name and title
Current projects
Skills and technologies
Social media links
Email address
Change Color Scheme
The README uses Tokyo Night theme. To change:
Find theme=tokyonight in README.md
Replace with: radical, dark, merko, gruvbox, dracula, monokai, vue, etc.
Modify Typing Animation
Edit the typing SVG text in README.md:
https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A9FEF7&center=true&vCenter=true&width=940&lines=YOUR+TEXT+HERE
🎨 Advanced Customizations
Add Wakatime Stats
Sign up at WakaTime
Install WakaTime extension in VS Code
Get your API key from WakaTime dashboard
Add to GitHub Secrets as WAKATIME_API_KEY
Update the wakatime username in README
Create Custom Badges
Use Shields.io to create custom badges:
![Custom Badge](https://img.shields.io/badge/Your-Badge-color?style=for-the-badge)
Add Spotify Integration
Set up Spotify README
Follow their setup instructions
Add the embed code to your README
🐛 Troubleshooting
Snake Animation Not Showing?
Check if Actions workflow completed successfully
Verify output branch was created
Make sure repository is public
Wait 5-10 minutes for GitHub cache to clear
Stats Not Updating?
GitHub API has rate limits
Stats update approximately every 15 minutes
Clear browser cache and refresh
Images Not Loading?
Check internet connection
Verify URLs are correct
Some services may be temporarily down
📚 Resources
GitHub Profile README Generator
Awesome GitHub Profile README
GitHub Stats API
Skill Icons
🤝 Contributing
Feel free to fork this and create your own version! If you make cool improvements, share them!
📞 Support
If you need help:
Open an issue in your repository
Check the resources above
Join GitHub Community discussions
Made with ❤️ by Deepak Rakshit
Happy Coding! 🚀