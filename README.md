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
