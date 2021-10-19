To run this "mini" web app
1. Clone this repository locally then push to your repository
2. Deploy the app with heroku or azure

If you use heroku to deploy the app:
1. Create account or login to heroku
2. Create new app
3. Fill the app name and choose a region
4. Choose deloyment method to github (if you use github) and choose the repo and the branch that contain this app
5. In the manual deploy section, click "Deploy Branch"
6. Click view to open deployed app and add "/docs" in the end of the URL to use it

If you use azure to deploy the app:
1. Create account or login to portal.azure.com
2. Locate App service and add
3. Fill the app name, region, etc and choose your service plan
4. In the "Configuration" option, open tab "General Settings" fill the "Startup Command" with startup.sh then save
5. In the "Deployment Center" option, choose source from External Git and connect to your github account (if you use github)
6. Choose app service build service and choose the repository and branch that contain this app then save
7.  In the "Overview" section click restart, after that open the URL and add "/docs" in the end of the URL