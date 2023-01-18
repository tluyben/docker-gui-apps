# Run GUI apps on Mac OS X m1 in Docker

## Why? 

1. Reproducible environments for devs. 
2. 

## Install 

- make sure you have docker / docker-compose installed
- install https://www.xquartz.org 
 - take the 2.8.5 beta for now as the others are very slow (bug, only fixed in 2.8.5beta, 2.8.1-4 are *very* slow)
- brew install socat 
- ./setup  and let it run 
- ./run-vscode or ./run-firefox or ./run-jupyter

This installs my plugins in vscode; check ./vscode/runvscode to see which plugins and add your own. Run 

- ./run-vscode --build 

to reinstall vscode with the new plugins. It does not uninstall plugins. 


