# 1. Make a project folder and enter it
mkdir levis-elevators && cd levis-elevators

# 2. Copy your downloaded file in and rename it to index.html
cp ~/Downloads/levis-elevators.html ./index.html

# 3. Turn the folder into a git repo
git init
git add index.html
git commit -m "Add Levi's Elevators site"

# 4. Create a new repo on GitHub named levis-elevators (via github.com/new),
#    then connect this folder to it and push
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/levis-elevators.git
git push -u origin main

# 5. Turn on GitHub Pages
#    Go to: github.com/YOUR-USERNAME/levis-elevators/settings/pages
#    Under "Branch", choose "main" and folder "/ (root)", then Save
