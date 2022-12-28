## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Tue Dec 27 2022 23:16:08 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-freestyle|
|**App Generator Version**<br>1.8.3|
|**Generation Platform**<br>SAP Business Application Studio|
|**Template Used**<br>simple|
|**Service Type**<br>None|
|**Service URL**<br>N/A
|**Module Name**<br>flplugin001|
|**Application Title**<br>System Details - Title|
|**Namespace**<br>com.sap.rig|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.109.3|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|

## flplugin001

A Fiori plugin
With this plugin you will display a customized text in the on-premise SAP Fiori Launchpad Header Title section

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```
NOTE - This is an FLP plugin so test files used for rendering the Fiori Launchpad Sandbox are missing, even if you run the start command you will not be able to simulate the plugin in BAS.

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)

### Deploying the plugin

-   In BAS terminal navigate to the webapp folder and run:

```
    npm run deploy-config
    npm run build
    npm run deploy

```


