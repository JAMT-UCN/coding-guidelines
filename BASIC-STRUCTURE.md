# Chat App Structure

## Basic folder structure

    .
    ├── /client             # React app (Important: the name of the app needs to be "client")
        ├── /pages
            └── ...
        └── /components
            ├── /common
                └── Menu.js
            └── ...
    ├── /routes             # Handles routing
        ├── auth.js
        ├── chat.js
        └── ...
    ├── /models             # Contains database models
        ├── User.js
        ├── Chat.js
        └── ...
    ├── /config             # Stores config files and keys
        ├── env.js
        └── dbKeys.js
    ├── /middleware         # Contains Node.js middleware files
        ├── ...
        └── ...
    ├── server.js           # Main
    └── README.md

## Naming conventions:
* Folders: Lowercase, with dashes `-` as spaces
* JS files (general): Camel-case
* Models and classes: Capitalized. If the name of a model (or class) is composed by more than one word, each word has to be capitalized and there should be no spaces between them
* .md files: Uppercase

### React frontend:
* Use functional components
* Use SASS!
    
