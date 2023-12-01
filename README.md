echo "# CulturalCrestEvents" >> README.md
mkdir html_files
echo "<html><body>Event Management Project</body></html>" > html_files/project\(event\ management\).html

git init
git add README.md html_files/project\(event\ management\).html
git commit -m "Initial commit for CulturalCrestEvents"
git branch -M main
git remote add origin https://github.com/nikhiljujare3/CulturalCrestEvents.git
git push -u origin main
