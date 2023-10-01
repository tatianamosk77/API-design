# API-design
Different types of API documentation are provided in this repository

### 1. JSON-RPC design.json 
The file contains designed JSON-RPC API documentation according to the task:

You are working on developing API for a data storage that stores sensitive user data. The system must provide the ability to add, retrieve and delete data, considering different access levels.

**Requirements to the method:**
 + Method name: manageSecretData
 + The method should take the folowing parameters:
    * action: action type (add, get, delete)
    * dataID: data identifier
    * userData: data to be added (optional)
    * accessLevel: access level (user, admin, superAdmin)
+ Depending on action and accessLevel, the method should return relevant errors or results. For example, only superAdmin can delete data.
