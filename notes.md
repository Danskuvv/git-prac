Id CommandLine

---

1 git clone https://github.com/mattpe/git-intro.git  
 2 cd git-intro  
 3 git remote remove origin  
 4 git remote add origin https://github.com/Danskuvv/git-prac.git  
 5 git commit -m "initial commit"  
 6 git push  
 7 git push --set-upstream origin main  
 8 history | grep "git " >> notes.md  
 9 history > notes.md  
 10 git commit -m "first commit"  
 11 git add notes.md  
 12 git commit -m "added 'notes' file"  
 13 git push  
 14 echo "step 10"  
 15 history -n 1 > notes.md  
 16 echo "step 10" > notes.md
New feature
new feature 2.0
