# singlePage_portfolio
# Here's how to correctly download and save the ZIP file:
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> Invoke-WebRequest `
>>   -Uri "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Project/Final_Project_V3/finalproject_startercode.zip" `
>>   -OutFile "finalproject_startercode.zip"
# To UNZIP THE FOLDER
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> Expand-Archive -Path "finalproject_startercode.zip" -DestinationPath "singlepagewebsite"
```
# course pushing to github
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git init
Initialized empty Git repository in C:/Users/HARIKRISHNA/Desktop/singlepage_Portfolio/.git/
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git remote add origin https://github.com/HARIKRISHNA95504/singlePage_portfolio.git
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git add .
warning: in the working copy of 'singlepagewebsite/html_finalprojimages/checkmark--outline.svg', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'singlepagewebsite/index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'singlepagewebsite/script.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'singlepagewebsite/style.css', LF will be replaced by CRLF the next time Git touches it
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git commit -m "Single Page Portfolio desing Through Coursera"
[master (root-commit) 086a515] Single Page Portfolio desing Through Coursera
 18 files changed, 532 insertions(+)
 create mode 100644 finalproject_startercode.zip
 create mode 100644 singlepagewebsite/html_finalprojimages/CSS3.png
 create mode 100644 singlepagewebsite/html_finalprojimages/bullet.png
 create mode 100644 singlepagewebsite/html_finalprojimages/checkmark--outline.svg
 create mode 100644 singlepagewebsite/html_finalprojimages/envelope.png
 create mode 100644 singlepagewebsite/html_finalprojimages/flash.png
 create mode 100644 singlepagewebsite/html_finalprojimages/home.png
 create mode 100644 singlepagewebsite/html_finalprojimages/html5.png
 create mode 100644 singlepagewebsite/html_finalprojimages/java.png
 create mode 100644 singlepagewebsite/html_finalprojimages/js.jpeg
 create mode 100644 singlepagewebsite/html_finalprojimages/node.png
 create mode 100644 singlepagewebsite/html_finalprojimages/phone.png
 create mode 100644 singlepagewebsite/html_finalprojimages/python.png
 create mode 100644 singlepagewebsite/html_finalprojimages/react.png
 create mode 100644 singlepagewebsite/html_finalprojimages/waving-hand.png
 create mode 100644 singlepagewebsite/index.html
 create mode 100644 singlepagewebsite/script.js
 create mode 100644 singlepagewebsite/style.css
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git checkout main
Switched to branch 'main'
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git pull origin main --rebase  
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 2.04 KiB | 47.00 KiB/s, done.
From https://github.com/HARIKRISHNA95504/singlePage_portfolio
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Successfully rebased and updated refs/heads/main.
```
```
PS C:\Users\HARIKRISHNA\Desktop\singlepage_Portfolio> git push -u origin main
Enumerating objects: 23, done.
Counting objects: 100% (23/23), done.
Delta compression using up to 4 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (22/22), 1.07 MiB | 179.00 KiB/s, done.
Total 22 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/HARIKRISHNA95504/singlePage_portfolio.git
   36b4f81..6b2de61  main -> main
branch 'main' set up to track 'origin/main'.
```

