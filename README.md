# Question Paper Formatter (Indian School Format)
throw away the hassle to type or copy-paste and make the whole question paper and then format it according to your needs, with our HTML/CSS/JAVA based app which can run on any windows system tailored to your needs, we've completely eliminated this inconsistency issue.

Refer to the demonstration video below to get a glimpse at the functionality and ease opf access this app delivers!


https://github.com/user-attachments/assets/3afe6b04-3c44-4e68-b34c-b5c82331a934


## why use our app? 
1. With our app just copy-paste or type your questions, school name, etc. in input specific fields and press generate button to get a already formatted word document in your PC in milliseconds.
2. The format works for almost every school.
3. Dynamic generator, can make question papers of any size as long as your PC can handle the large amount of questions, theoretically it has no limits. 

## is it safe? 
1. Sure, this is a standalone windows application which does not require any internet connection and extensive access of your PC's drives and root directory. All it cares about is the folder where it is situated/kept in your PC.
2. 2. Made by an established programmer and youtube content creator "FrigonTech", who's been commited to making service based and inconsistency eliminating tools, applications and content for over 5 years.
  
### 1. Guide to building the application from source,
a. Setting up 1st User-Interface (Electron based); Navigate to GUI-1 folder:
``` 
cd GUI-1
```
b. Initialize NPM here:
```
npm init -y
```
c. Install Electron:
```
 npm install electron --save-dev
```
d. Your 'package.json' should look like this:
```
{
  "name": "gui-1",
  "main": "main.js",
  "scripts": {
    "start": "electron ."
  }
}
```
e. Finally from this directory you can start the electron software, note that you can only start the electron GUI from this folder: 
```
npm start
```

f. to build the electron version:
```
npm install electron-builder --save-dev
```
   then run the command to get this GUI built in a 'dist' folder,
```
npm run build
```
  
#Enjoy!
