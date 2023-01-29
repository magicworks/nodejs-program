 
 # Template to run a Node JS program as a command-line tool

This is a Node JS project template to run a javascript file as a command-line tool. It consists of a package manager file and `/bin/program.js` file which is going to be executed by running the command name `program`.

## Installation
Install node packages

```
npm install
```
**Open the package.json file, locate the bin section and change the command-line tool name "program" to your command name.

```json
"bin" : {
    "program" : "index.js"
} 
```
Change the file permission of the file that's going to run the program. 
```
chmod +x program.js
```
Run command to link projects

```
npm link
```
Run your command name and get a "Hi There!" message on CLI

```
program
```

Add your code to `/bin/program.js` file.

