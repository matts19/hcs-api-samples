# hcs-api-samples

**OVERVIEW**

This collection has samples showing how to interact with the alpha version of the REST API for the Horizon Service. These REST API samples are intended to serve as starting guides for developers. These are not an exhaustive list of APIs available or a substitute for REST API documentation. The Repository contains a POSTMAN Collection (HSAPI.postman_collection.json) showcasing APIs as well as an Environment File(Horizon_Service_API_Env.postman_environment). The POSTMAN Collection is organized into folders for the following areas: Auth, Tenant, Pod and Assignment. The Environment File has variables that capture the value of tokens and ids for various domain entities such as pods, assignments for use in subsequent API calls. 

**REQUIREMENTS**

The alpha version of the API for Horizon Service allows working with Horizon Enterprise assignments that can be managed from the Horizon Control Plane. API users need to have registered for the Horizon Service in CSP and have a customer account created in Horizon Control Plane. The CSP and Horizon Control Plane credentials, pod and assignment names should be updated in the Environment File after being imported to POSTMAN. Values for other variables are automatically captured from the responses returned by API invocations. 
The alpha version of the API for Horizon Service allow working with Horizon Enterprise Assignments that can be Managed from the Horizon Control Plane. API users need to have registered for the Horizon Service in CSP and have a Customer account created in Hydra.
The CSP and Horizon Control Plane credentials, Pod and Assignment Names should be updated in the Environment File after being imported to POSTMAN. Values for other variables are automatically captured from the responses. (List of variables set.)

**INSTALLATION**

The POSTMAN collections and environment file in the included folders were built using the Postman client. It is highly recommended to install the latest version of the Postman client.

Once installed, launch the Postman client and select the Import button in the upper left corner. This should open an Import dialog box, shown below. You can either Drag and Drop the json files or use the Choose files button to open the Postman Collection and Environment JSON files. 

You can explore the POSTMAN documentation here for more details about how to import POSTMAN data here : https://learning.getpostman.com/docs/postman/collections/data_formats/#importing-postman-data.  
