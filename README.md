
## Udacity Project Instructions (For Student)

You are expected to do the following to complete this project:

1. [x] Create a Resource Group in Azure.
2. [x] Create an SQL Database in Azure that contains a user table, an article table, and data in each table (populated with the scripts provided in the SQL Scripts folder).
    - [x] Provide a screenshot of the populated tables as detailed further below.
3. [x] Create a Storage Container in Azure for `images` to be stored in a container.
    - [x] Provide a screenshot of the storage endpoint URL as detailed further below.
4. [x] Add functionality to the Sign In With Microsoft button. 
    - [x] This will require completing TODOs in `views.py` with the `msal` library, along with appropriate registration in Azure Active Directory.
5. [x] Choose to use either a VM or App Service to deploy the FlaskWebProject to Azure. Complete the analysis template in `WRITEUP.md` (or include in the README) to compare the two options, as well as detail your reasoning behind choosing one or the other. Once you have made your choice, go through with deployment.
6. [x] Add logging for whether users successfully or unsuccessfully logged in.
    - [x] This will require completing TODOs in `__init__.py`, as well as adding logging where desired in `views.py`.
7. [x] To prove that the application in on Azure and working, go to the URL of your deployed app, log in using the credentials in this README, click the Create button, and create an article with the following data:
	- Title: "Hello World!"
	- Author: "Jane Doe"
	- Body: "My name is Jane Doe and this is my first article!"
	- Upload an image of your choice. Must be either a .png or .jpg.
   After saving, click back on the article you created and provide a screenshot proving that it was created successfully. Please also make sure the URL is present in the screenshot.
8. [x] Log into the Azure Portal, go to your Resource Group, and provide a screenshot including all of the resources that were created to complete this project. (see sample screenshot in "example_images" folder)
9. [x] Take a screenshot of the Redirect URIs entered for your registered app, related to the MS Login button.
10. [x] Take a screenshot of your logs (can be from the Log stream in Azure) showing logging from an attempt to sign in with an invalid login, as well as a valid login.


