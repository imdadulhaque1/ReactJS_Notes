# ReactJS_Notes
## Notes:
For run reactJS must have instalt **nodeJS** otherwise **reactJS** doesn't work. So, click [HERE](https://github.com/imdadulhaque1/distributions) or use the below command install **nodeJS** on **Ubuntu** Operating system.

                `curl -sL https://deb.nodesource.com/setup_15.x | sudo -E bash -`

                `sudo apt-get install -y nodejs`
                
Now check the version of **nodeJS**, using `node -v` and also check **npm** version using `npm -v` . 

**Mind it:** Using the above command to install **nodeJS**, **npm** install by default. Or, setup **npm** and maintains below command of installing procedure.
# npm setup: 
`sudo npm i create-react-app`
# Create React App: 
`npx create-react-app app_name`
# Entered in created app: 
`cd app_name`
# Run React app: 
`npm start`
# After updated anythings / Changes anythings need to run below command
- `git add .`
- `git commit -m "Updated something"`
- `git push -u origin master`

# For installing, run the below command
`npm install --save react-router react-router-dom`

# Below some of the important Git Command Link
1. [Git Command 1](https://github.com/imdadulhaque1/Git_Command_1) 
2. [Git Command 2](https://github.com/imdadulhaque1/Git_Command_2)


# React Project deploy architecture from starting to ending using comand
Follow the steps and that's are given below,
1. **Create react app:** `npm init react-app app_name`
2. **Install gh-pages:** `npm install gh-pages --save-dev`
3. **add homepage in _package.json_:** `"homwpage": "http://imdadulhaque1.github.io/app_name"`
4. **Add predeploy and deploy inside _scripts_ in _package.json_:**
                                                                  `"predeploy": "npm run build",`
                                                                   `"deploy": "gh-pages -d build",`
5. **Need to initialize the app:** `git init`
6. **Connected the github repository with created app:** `git remote add origin https://github.com/imdadulhaque1/app_name.git`
7. Now I should works to build up the projects
8. **Run deploy:** `npm run deploy`
9. **Put the app in github:** `git push -u origin masters`

# Install some packages
1. **Install Bootstrap:** `npm install bootstatp@4.5.0 --save`
2. **Install reactstrap:** `npm install reactstrap@8.5.1 --save`
3. **Install react-popper:** `npm install react-popper@2.2.3 --save`
4. **Install together:** `npm install bootstrap@4.5.0 reactstrap@8.5.1 react-popper@2.2.3 --save`
5. **Install Date Format:** `npm install dateformat --save`
6. **Install Font-Awesome:** `npm install font-awesome --save`

# yarn Install and Uninstall
1. **Install:** [CLICK HERE](https://linuxhint.com/install_yarn_ubuntu/)
1. **Uninstall:** `npm uninstall -g yarn`

# For connecting Redux need to install some packages and that's are given below,
1. **Install redux:** `npm install redux --save`
2. **Install react-redux for supporting redux in react files:** `npm install react-redux --save`
3. **For Installing middleware use the command:** `npm install redux-logger --save`
4.  **Install redux-thunk:** `npm i redux-thunk`
5.  **Install react-redux-form:** `npm i react-redux-form`


# Node and NPM install in Windows:
1. **Install Node:** [CLICK HERE](https://nodejs.org/en/download/) to download  and **check the version:** `node -v`
2. **Install React from terminal Globally:** `npm install -g create-react-app`
3. **VS Code Package Install:** __

# REST API setting up:
1. **Install json-server globally:** `npm install json-server -g`

# Host React Projects in github:
Should follow This [LINK](https://create-react-app.dev/docs/deployment) to deploy.
Or, After push the projects, follow the below steps,
1. Open the `package.json` and add a `homepage` field below `name` for the project:
    `"homepage": "https://imdadulhaque1.github.io/project_name"`
    
2. Install `gh-pages` and add `deploy` to `scripts` in `package.json` :
    `npm install --save gh-pages`
    
    For `yarn`: `yarn add gh-pages`
3. Add the scripts in `package.json`:
      `"scripts":{
      
          "predeploy": "npm run build",
          
          "deploy": "gh-pages -d build",
      }
      `
      
4. Deploy the site by running `npm run deploy`
