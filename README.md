Overview
--------
Android demo using the Google Geocoding, Elevation and Civic Information APIs: the project builds a simple Android application that gives geocoding and elevation data, plus a complete list of elected officials (in the US at least), for a given address string. The application will run fine on a connected device or AVD emulator (use an Android-21 system image).

Using Google APIs
-----------------
You will need a Google API key to access the [Geocoding API](https://developers.google.com/maps/documentation/geocoding/), [Elevation API](https://developers.google.com/maps/documentation/elevation/) and [Google Civic Information API](https://developers.google.com/civic-information/): these services have courtesy limits, which allow limited use free of charge. Use the [Google API Console](https://code.google.com/apis/console) to create a Google API project, add the required services (APIs & Auth -> API) and then create an API Key (APIs & Auth -> Credentials). Create a Browser key and leaved the Allowed Referers field blank.

Copy your API key to the following file `app/src/main/java/com/example/appdynamics/placesdemo/GooglePlacesKey.java`

Gradle Builds
-------------
1. To build: `gradle clean build`
2. To install: `gradle installDebug`
