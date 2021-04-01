To get started, clone the master branch of the repository. Then type the following commands, you need NPM (https://www.npmjs.com/get-npm) installed for this to work.
npm install
npm start

"npm install" downloads all the Node.JS libraries required for the program to work.
"npm start" starts the program.
The program will start in development mode and save all the config files (master password, data, theme, etc.) to %localappdata%/PassVaultDev

If you would like to package the program into an executable, use one of the following commands:
npm run package-mac
npm run package-win32
npm run package-win64
npm run package-linux

The program will start in production mode and save all the config files to %localappdata%/PassVault