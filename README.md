
## Instructions
### Building and running
Use the following sequence of steps to build and run the code:
1. Install nodejs
2. `npm install` # install dependencies
2. `npm run build` # builds js files
3. `npm run roll` # combine project into a single file to upload to screeps
4. Upload the file to a screeps server. This can be done using `npm run push` if you have a .screeps.yml file (https://github.com/screepers/node-screeps-api)

NOTE: For step 4 to work, set up the environment variables for host, username and password (refer to screepsNoCreds.yml).
For setting up Github secrets, please refer to the following link: https://docs.github.com/en/actions/security-guides/encrypted-secrets 

