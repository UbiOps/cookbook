# INSERT YOUR TITLE

In this example we will show you the following:
- How to make ...


## INSERT WHAT YOU CREATE

The resulting pipeline is made up of the following deployments:

| Deployment | Function |
|-------|----------|
| deployment-1-name | INSERT DESCRIPTION |
| deployment-2-name | INSERT DESCRIPTION |

The pipeline looks like this:
INSERT PICTURE


## How does it work?

**Step 1:** Login to your UbiOps account at https://app.ubiops.com/ and create an API token with project editor
admin rights. To do so, click on *Users & permissions* in the navigation panel, and then click on *API tokens*.
Click on *create token* to create a new token.

![Creating an API token](api_token_screenshot.png)

Give your new token a name, save the token in safe place and assign the following roles to the token: project editor and blob admin.
These roles can be assigned on project level.

**Step 2:** Download the *INSERT FOLDER NAME WITH THE DOWNLOAD LINK* folder and open *INSERT NOTEBOOK*. In the notebook you will find a space
to enter your API token and the name of your project in UbiOps. Paste the saved API token in the notebook in the indicated spot
and enter the name of the project in your UbiOps environment. This project name can be found in the top of your screen in the
WebApp. In the image in step 1 the project name is *scikit-example*.

**Step 3:** Run the Jupyter notebook *INSERT NAME OF NOTEBOOK* and everything will be automatically deployed to your UbiOps environment! 
Afterwards you can explore the code in the notebook or explore the application in the WebApp.
