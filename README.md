# antora-playbook
## Antora Playbook POC

### Setting up Playbook: 
1) Download and install the latest Node.js from https://nodejs.org/en/download
2) Install Antora using the command 'npx antora -v'
3) Install the Antora site generator with command 'npm i @antora/lunr-extension'
Note: Use command 'npm ls -g --depth=0' to list all antora installed packages

### Generating the Site:
1) type command 'npx antora --fetch antora-playbook.yml'

### Setting up GUI bundle: 
1) install gulp using command 'npm install -g gulp-cli'
Note: Check gulp by using command 'gulp --tasks-simple'

### Gulp Commands:
gulp preview:build - build and preview the GUI bundle
gulp preview - preview the GUI bundle
gulp bundle - generate the zip bundle



