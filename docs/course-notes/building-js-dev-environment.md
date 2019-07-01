# Building a JavaScript Development Environment

<-- back to Mobile Web Specialist homepage

## Supporting Links
* https://app.pluralsight.com/library/courses/javascript-development-environment/  
* 

## Module 1. Course Overview
## Module 2. You Need a Starter Kit
## Module 3. Editors and Configuration
Things to take into consideration when chosing a JS editor:
* strong support of ES6+: autocompletion, parse es6 imports...
* framework intelligence: support for recent libraries like node, react...
* **built-in terminal**
### Popular JS Editor
* Atom
* Bracket
* WebStorm
* **VSCode**
Create .editorconfig file and put it in the root of the project to maintain automated consistence among team members. More about .editorconfig on www.editorconfig.org.
## Module 4. Package Management
Every popular language has its own package management nowadays.
For security purpose install nsp: ```npm install -g nsp```
Run ```nsp check``` to check for known vulnerability of your packages.
**Note** nsp has been replaced by npm audit
## Module 5. Development Web Server
### Web servers
* http-server
* live-server
* **Express**
* budo
* Webpack dev server
* Browsersync

For the purpose of this course we configure Express.

### Sharing work-in-progress
Browsersync is a handy way to share your work with your co-workers. But, it doesn't expose public IP to help test your work outside of your network. 
The solutions below will help you quickly share/expose your work to the public web:
* **Localtunnel**: easiest setup and ultraversatile
* ngrok: easy setup and secure
* Now: persistent host
* Surge: host static files, persistent host

Can also be used for production: ngrok and Surge

## Module 6. Automation
## Module 7. Transpilling
## Module 8. Building
## Module 9. Linting
## Module 10. Testing and Continuous Integration
## Module 11. HTTP Calls
## Module 12. Project Structure
## Module 13. Production Build
## Module 14. Production Deploy 
