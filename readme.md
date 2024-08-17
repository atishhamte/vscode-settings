### How to do vscode settings
 - Replace settings.json of vscode
 - Install **JetBrains Mono** font
 - Install **Custom CSS and JS Loader** extension
 - Put *custom-vscode.css* and *vscode-script.js* file in local directory
 - Change the path on in the settings.json file
    ```
    "vscode_custom_css.imports": [
        "file:///path-to-file/custom-vscode.css",
        "file:///path-to-file/vscode-script.js"
    ],
 - Enable the **Custom CSS and JS Loader** extension from command palette
 - Make terminal changes in ~/.zshrc file to get Hybrid Ubuntu-like and zshrc style Prompt without hostname
    ```
    PROMPT='%F{green}%n%f:%F{yellow}%1~%f %F{cyan}%#%f '
 - Restart vscode and terminal to see changes


### Used extensions
 1. Custom CSS and JS Loader
 2. Codesnap
 3. Color Highlight
 4. GitLens
 5. Live server
 6. Material Theme Icons - Free
 7. Prettier
