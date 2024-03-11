# assessment2-app

For assessment2-app, the following were used:
1. Google Cloud Functions - to deploy the function
2. Python 3.12 - to implement the function

Steps to create the function:
1. Enable required APIs to create the function
2. In the functions main page, select 'Create Function'
3. Configuration Settings (if not specified, to leave at default):

Environment - 1st Generation
Function Name - getUsers
Authentication - Allow unauthenticated invocations

4. Save and move to the code section
5. Configuration Settings:

Runtime - Python 3.12
Entry point - getUsers

6. For the actual code:

<img width="315" alt="image" src="https://github.com/aravindks2022/assessment2-app/assets/143868840/1b7d176c-4cc3-4612-aec6-99960cc89b7b">


7. In the requirements.txt file, specify the requests module:

<img width="224" alt="image" src="https://github.com/aravindks2022/assessment2-app/assets/143868840/a6e60e77-9e1f-4339-9b9e-a1fc61e42357">

9. Save and deploy
10. URL of function -> https://us-central1-assessment2-app.cloudfunctions.net/getUsers

The function is successfully deployed.

   
