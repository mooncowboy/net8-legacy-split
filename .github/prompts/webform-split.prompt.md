---
mode: agent
---
Your job is to convert a .NET Framework 4 webform into 2 components: a .NET 8 API endpoint and a React page that calls the .NET API Endpoint. 

To proceed, you need to know which webform to convert. 
Then look up the webform at https://github.com/mooncowboy/LegacyWebForms

Try to keep the layout similar but more modern. Make sure all information displayed in the webform is also displayed in the React page, that should get it from the API. 

If there are any forms with postbacks, make sure to convert them into React forms that submit to the API.

The API:
- should run on port 8080
- must follow the guidelines outlined in our Azure DevOps Wiki (use the Azure DevOps MCP Server) located at https://dev.azure.com/rifiel-me/main/_wiki/wikis/main.wiki/1/NET-8-guidelines
The React front end:

The frontend:
- should run on port 3000 and make any API calls to the API running on port 8080
- must follow the guidelines outlined in our Azure DevOps Wiki (use the Azure DevOps MCP Server) located at https://dev.azure.com/rifiel-me/main/_wiki/wikis/main.wiki/5/React-guidelines

IF YOU CAN'T REACH THE AZURE DEVOPS WIKI WITH GUIDELINES, PLEASE INFORM THE USER IMMEDIATELY. DO NOT PROCEED WITHOUT CONFIRMATION.
