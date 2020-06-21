# Auth0 Android Login Quickstart

Implementation of [Auth0 Android: Login Quickstart Tutorial](https://auth0.com/docs/quickstart/native/android/00-login)

### Requirements

This sample app runs on Android versions 21 and above.

# Setup

## Run the APK using the sample-apps Auth0 tenant (requires access)
1. Download the [`app-debug.apk`](./app-debug.apk)
2. Open Android Studio, select `Profile or debug APK`, and the `app-debug.apk` file.
3. Click the green `Run` button at the top of the window to run `app-debug`.

## OR

## Run the project using your own Auth0 credentials
1. Clone this [repo](https://github.com/egconley/auth0-android-quickstart.git) down to your local machine.
2. Create a `res/values/strings.xml.example` file in your project resources. 
3. Add the Auth0 Domain and Client ID values present on your [client settings](https://manage.auth0.com/#/clients) page.

> Given a Domain value of `"myuser.auth0.com"` and a Client ID value of `"1234567890abcdf"`, the file would look like:

> ```xml
> <resources>
>     <!-- ... -->
>     <string name="com_auth0_client_id">1234567890abcdf</string>
>     <string name="com_auth0_domain">myuser.auth0.com</string>
> </resources>
> ```
4. Click the green `Run` button at the top of the window to build and run the app.
