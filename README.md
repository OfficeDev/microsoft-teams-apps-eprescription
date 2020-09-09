---
page_type: sample
products:
- Power Apps
- Power Automate
- SharePoint
description: E-Prescriptions uses the Booking app to make appointments during which doctors can generate e-prescriptions and email them to the consulting patients.
urlFragment: microsoft-teams-apps-eprescription
---

# E-Prescriptions App Template

| [Documentation](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/Home) | [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/Deployment-Guide) | [Architecture](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/Solution-Overview) |
| ---- | ---- | ---- |

Hospitals and healthcare institutions are increasingly performing tele-consultation or virtual consults so that doctors can connect with patients remotely. Each appointment results in a prescription being generated. Unlike physical appointments that enable doctors or admins to hand out physical prescriptions to patients, a virtual consult makes this process challenging since admins need to capture prescriptions details from doctors and send these to patients.

The E-prescriptions app is designed to automate the process of sending prescriptions to patients in an electronic format without any manual intervention from admins. Doctors can pull up their appointment details and quickly generate an e-prescription for each appointment which lands in a patient’s email inbox.

Here is a high-level overview of the app:

1. Admins can manage e-prescriptions through an admin app including management of doctor records and e-prescription format.
  ![Welcome page](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/images/DoctorDatabase.PNG)

2. Doctors can view all appointments for a day in a single list view. For each appointment, an e-prescription can be filled out, previewed and then sent as an email to the patient along with any attachments. The doctors can also view the generated e-prescriptions.
![Consult page](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/images/Consult.PNG)

## Legal notice

This app template is provided under the [MIT License](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/blob/master/LICENSE) terms.  In addition to these terms, by using this app template you agree to the following:

- You, not Microsoft, will license the use of your app to users or organization. 

- This app template is not intended to substitute your own regulatory due diligence or make you or your app compliant with respect to any applicable regulations, including but not limited to privacy, healthcare, employment, or financial regulations.

- You are responsible for complying with all applicable privacy and security regulations including those related to use, collection and handling of any personal data by your app. This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization. Where applicable, you may be responsible for data related incidents or data subject requests for data collected through your app.

- Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository. Microsoft’s general trademark guidelines can be found [here](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general.aspx).

- If the app template enables access to any Microsoft Internet-based services (e.g., Office365), use of those services will be subject to the separately-provided terms of use. In such cases, Microsoft may collect telemetry data related to app template usage and operation. Use and handling of telemetry data will be performed in accordance with such terms of use.

- Use of this template does not guarantee acceptance of your app to the Teams app store. To make this app available in the Teams app store, you will have to comply with the [submission and validation process](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish), and all associated requirements such as including your own privacy statement and terms of use for your app.



## Getting started

Begin with the [Solution overview](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/Solution-overview) to read about what the app does and how it works.

When you're ready to try out E-Prescriptions app, or to use it in your own organization, follow the steps in the [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-eprescription/wiki/Deployment-guide).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
