echo "# CulturalCrestEvents" >> README.md   # Create or modify README.md as needed
mkdir html_files                           # Create a folder named html_files
echo "<html><body>Event Management Project</body></html>" > html_files/project(event management).html   # Create the HTML file

git init                                   # Initialize a new Git repository
git add README.md html_files/project\(event\ management\).html   # Add files to staging (escape spaces in the file name)
git commit -m "Initial commit for CulturalCrestEvents"   # Commit changes
git branch -M main                         # Rename the default branch to "main"
git remote add origin https://github.com/nikhiljujare3/CulturalCrestEvents.git   # Add the remote repository
git push -u origin main                    # Push changes to the remote repository
