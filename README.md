#Useful Git commands

If the problem is "main and master are entirely different commit histories.", the following will work

git checkout master   
git branch main master -f    
git checkout main  
git push origin main -f 