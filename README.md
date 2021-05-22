# AngularJS_intelligence_-enable_in_VScode
This is the procedure through which angularjs intelligence can be added to Vscode

Install the typings package through npm. Install it globally.

# npm install -g typings

Install the Angular specific typings on the directory of your project.

# typings install dt~angular --save

The typigs folder and files will be created on your projects folder.
The typings.json file will be created too. Eventually this will be filled up by configuration entries but since we are just starting out and we are only interested in intellisense, this is blank.

# Create the jsconfig.json file in the projects root directory'

Validate that the AngularJS intellisense is working. 
