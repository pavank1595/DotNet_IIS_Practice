Create and configure dev and test environments
Create a sample dotnet webapp
Leave the master branch empty initially
Create a development branch
Commit and push the code to github onto the development branch
Configure azure pipelines to deploy code to dev and test environments from develpment branch
Regularly monitor ci and cd pipelines and regularly check the application
After the applicatin is stable in dev and test environments, create a release branch from development branch
Create and configure production environment
Deploy the application to the production environment from release branch
Once the deployment is stable merge the release branch code to the master branch
Create a version tag for the application as v1.0
Commit and push the tag to github
Merge the master branch code back into the development branch 
Run the application and access it through web browser

Make changes or add some addional features for the ongoing application version
Create a feature branch from the master branch
Configure azure pipeline to trigger from feature branch