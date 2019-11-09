# This project has Detailed Network diagram and script for Installing Azure apim in Vnet

# Scenario
To deploy APIM with API gateway in a vnet so that it is accessible via a custom domain and is secured with ddos and other protections like NSG for only specific port and certificates being linked from Keyvault.

It also contains a draw.io diagram to edit/ adapt to new requirements.



# High level Diagram
![High level diagram](https://github.com/apurvc/AzureAPIMAppGW/blob/master/secured%20apim%20management.png)

# Low level Diagram
![Low level diagram](https://github.com/apurvc/AzureAPIMAppGW/blob/master/Untitled%20Diagram.png)

# Deployment
This PowerShell script deploys - 

- Azure Application Gateway
- Azure API Management in Internal VNET mode
- TBD: Update script to include NSG 

As per the diagram Any API's hosted will have a base URL https://dev.apim.com.

Ref:
- https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-internal-vnet
- https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway
