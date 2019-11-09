# This project has script for Installing Azure apim in Vnet



# Scenario
To deploy APIM with API gateway against a vnet so that it is not externally accessible and is secured with ddos and other protections 

![High level diagram](https://github.com/apurvc/AzureAPIMAppGW/blob/master/secured%20apim%20management.png)

![Low level diagram](https://github.com/apurvc/AzureAPIMAppGW/blob/master/Untitled%20Diagram.png)

# Deployment
This PowerShell script deploys - 

- Azure Application Gateway
- Azure API Management in Internal VNET mode

Any API's hosted will have a base URL https://api.example.org.
