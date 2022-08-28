How to deploye Flask app on Azure App Service.
Best ways which are ested explained below.

1. Create Flask project and run it on local using "flask run" command.
2. Once everything is good with No errors or warnings, export all the libraries using "pip freez > requirements.txt" command. Which stores all the required libraries and its versions in the text file.
3. Create a "commit" and "push" the code to Github repository
4. Once done in Azure create an "App service", "App service plan" and the "Applications insights service" (optional) and link it manually or Use VSCode to do the same.
5. Then go to "App service > Deployment Center > Source=GitHub, Select Repo, Select Branch and the python version (In this case Python 3.9)".
6. Save it and then it starts the deployment from GitHub. We can see the same in the Github repository under Axtions>Workflows.
7. We can preview the sites after that usin the URL from the Azure App Service.
