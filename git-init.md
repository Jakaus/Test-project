## Create a new repository on the command line  

echo "# Test-project" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:PotatoRush/Test-project.git  
git push -u origin main // only need "git push" after init push  


## Push an existing repository from the command line

git remote add origin git@github.com:PotatoRush/Test-project.git  
git branch -M main  
git push -u origin main // only need "git push" after init push  

## Test