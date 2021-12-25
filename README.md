# FrontEndMentor 3-column preview card component challenge hub

## Proposal
- It's an exercice propose by the site : FrontendMentor
- The link : https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-

## Tools used
1. HTML
2. CSS and SCSS

## Execute the project
1. Download the project
2. Go to the project repository
3. Click on index.html file

## Reload css
1. Open visual studio
2. Create a file .vscode/tasks.json at the root of the project
3. Fill the file with the following text:
```json
{
    // See https://go.microsoft.com/fwlink/?LinkId=733558
    // for the documentation about the tasks.json format
    "version": "2.0.0",
    "tasks": [
        {
            "label": "verify",
            "type": "shell",
            "command": "sass css/main.scss css/main.css",
            "group": "build"
        }
    ]
}
```
4. Do Ctrl-Shift-B
5. Reload the page