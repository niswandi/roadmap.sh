# roadmap.sh
echo "# roadmap" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/niswandi/roadmap.git
git push -u origin main
