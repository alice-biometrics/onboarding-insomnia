# onboarding-insomnia

ALiCE Onboarding API provides the core functionalities of an onboarding process. It includes:

* Creation and management of user profiles for onboarding
* Adding identity documents, driving licences, passports, residence cards, etc. associated with a user, as well as selfie videos.
* Automatic processing and reading of relevant information from those documents for onboarding processes.
* Identity verification of the user against the photographs of the documents, providing a facial matching score for each document.
* PAD analysis to detect signs of spoofing attacks through printed photographs or pictures and videos shown on screen.
* Generation of reports with all the information extracted from a user for onboarding processes.

## ALiCE Onboarding API

Swagger Info: 

* [Auth](https://apis.alicebiometrics.com/auth/ui/#/)
* [Onboarding](https://apis.alicebiometrics.com/onboarding/ui/#/)


## Onboarding Workflow

![Onboarding Workflow](images/onboarding_api_workflow.png)

## Getting Started

The following Insomnia Workspace will help you to better understand the flow of the API.

1. Download the Workspace project (`Insomnia v4 - JSON`) [here](demo-alice-onboarding-insomnia.zip)
2. Import the Workspace in the Insomnia. `Import/Export -> Import Data -> From File`
3. Activate just installed Workspace Demo ALiCE Onboarding.
4. Configure your API TOKEN. `Manage Environments -> Base Environment -> apikey_client`

![Insomnia Example Configuration](images/insomnia_example_configuration.png)

5. Check following steps to complete an ALiCE Onboarding using Insomnia:

![Insomnia Guide](images/insomnia_guide.png)
