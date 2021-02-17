Jira Prep
Top of Lab
Sign up for free Atlassian Cloud account at https://www.atlassian.com/try/cloud/signup?bundle=jira-software&edition=free
Note If your company email is already associated with an Atlassian account, to follow this guide:
Open an incognito browser window
Navigate to https://www.atlassian.com/try/cloud/signup?bundle=jira-software&edition=free
Use a personal or other email account to create an account
During the auto-setup choose the following options
I am experienced with Jira
My team is experienced with agile methodologies
We spend our time working on fixing bugs
We have a flexible schedule to finish our work
Create a new project & choose a Kanban project
Project Name = APPSEC
Project Key = APPSEC
Note The 'Jira Project' field in the .yml file corresponds to this 'Project Key' and is case sensitive
Create an API token from your Atlassian account:
Log in to https://id.atlassian.com/manage-profile/security/api-tokens
Click Create API token.
From the dialog that appears, enter ‘CxFlow’ and click Create.
Click Copy to clipboard, then paste the token to your script, or elsewhere to save: it should be pasted into the token: <> of the application.yml
Create a custom field for this project and issue type screen by clicking the settings wheel in the top right corner
Click Issues > Custom Fields > Create Custom Field
Click Labels and give it a name “Application”
Description = CxSAST Project
Select the checkboxes next to APPSEC: Kanban Bug Screen & APPSEC: Kanban Default Issue Screen
Click Update
Create another custom field for Category
Name = Category
Description = CxSAST Vulnerability Type
Select the checkboxes next to APPSEC: Kanban Bug Screen & APPSEC: Kanban Default Issue Screen
Click Update
