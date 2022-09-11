# useful-command-linux-windows-dev

## NPM
- npm init
- npm install -g express (npm i -g express)
- npm install express (npm i express)
- npm install (npm i) (The depedencies to install is in the package.json file)
- npm install express --save (This will cause NPM to add the dependency entry in package.json for you)
- npm update express
- npm uninstall express
- npm ls
- npm -g ls
- npm audit (Running this command will scan the package.json file and submit the list of dependencies to the default NPM registry requesting a report on any known vulnerabilities in them.)
- npm audit fix (Update any vulnerable packages with the newest available version that hasn’t had the vulnerability reported in it.)
## SSH
- ssh -R 80:localhost:8080 localhost.run (Expose my service in port 8080 to the internet in port 80) [[localhost.run](http://localhost.run/)]

## Outils pour windows

- chocolatey is a package manager for windows like apt or pacman [chocolatey](https://lecrabeinfo.net/chocolatey-gestionnaire-paquets-windows.html)
`choco search --by-id-only firefox`
