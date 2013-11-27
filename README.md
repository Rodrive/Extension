Extension
=========

This Rubedo example extension shows how to :

- build a fresh new theme, coming with its css, js and images files
- build a new functionnal block

You can install an extension :

- from the source code :
1) drop the source code in the extensions directory

- using composer :
1) copy composer.extension.json.dist to composer.extension.json
2) add your extension repository in composer.extension.json
3) run install-extensions.bat or install-extensions.sh depending on your OS

End the installation process by cleaning the Rubedo cache (from the back-office in the supervision module or by manually cleaning cache/config directory)

For more details about building blocks please read the following guide : https://rubedo.atlassian.net/wiki/display/RBT/Adding+block+types+to+your+extension
