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
