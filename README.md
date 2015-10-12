# StreetHawk Android SDK

## Introduction
The repository hosts reference library to be used for the Andorid applicatios created using Eclipse IDE. Below mentioned are the StreetHawk SDK modules. Click [here](https://streethawk.freshdesk.com/support/solutions/folders/5000273033) for detailed documentation on StreetHawk SDK

| Modules             | Description                                                                                                                  |
|----------------------|------------------------------------------------------------------------------------------------------------------------------|
| streethawkcore               |Application Analytics |
| streethawkgrowth                | Viral and organic growth|
| streethawkpush                | Push messaging|
| streethawkbeacon              | Beacons|
| streethawklocation                 |Location based campaigns, Work and Home location of user|
| streethawk feeds              | Feeds|
                            
## Installation

1. Download the contents of repo. The repo contains all the module of StreetHawk SDK. You may choose to import all or any selected combination of modules in your project.
2. Right click on your application project - Properties - Android,in Library section, click on Add and select SDK modules you wish to add in your project.
3. Add Google Play Services in your application.
* Install Google Play Services from Android’s SDK Manager by selecting Google Play services in the Extras section.
* In Eclipse, click on File - Import - Android - Existing Android Code Into Workspace - browse to Android the SDK Folder.
* Select extras - google - google_play_services - libproject and click on finish.
* Right click on your application project - Properties - Android, click Add in Library section and select google-play-services_lib.For more details about setting up of Google play-services please refer to Google Play Services link
4. Enable manifest merger by adding below mentioned statement in project.properties file of your project.
```
manifestmerger.enabled=true
```
## Detailed documentation
More documents on [StreetHawk freshdesk](https://streethawk.freshdesk.com/helpdesk). 
## StreetHawk web console
Register App on [StreetHawk web console](https://console.streethawk.com). 
## Author

StreetHawk, support@streethawk.com

## License

The StreetHawk Android SDK is available under the LGPL license.
