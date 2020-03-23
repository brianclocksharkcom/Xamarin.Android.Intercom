# Xamarin.Android.Intercom.V6
Xamarin package of Intercom V 6.1 for Android

This package pulls in the .aar files for Intercom from the following repo:
https://github.com/intercom/intercom-android

There is then a binding project for each type using version Lollipop v5.0 of android (internal 21).

There is also a nuget commandline to package together the dlls.  The nuget package is published in a public repo under "xamarin.intercom.V6" (xamarin.intercom was already taken).

*Note, the Base.Transitive and Fcm .aar files are not included as they were not needed for the project, however you should be able to add them to the nuget package and publish locally.
