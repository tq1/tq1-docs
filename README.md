# TQ1 DOCS

## What is TQ1?

TQ1 a web platform made by Taqtile used to manage mobile-marketing campaigns. By using it you'll be able to create and schedule push notification campaigns, either by sending targeted notifications or by creating geofences that will target users according to their location.

It consists of 3 main parts: the SDKs, the admin and the server.

In this docs you will find the links to all our documentation.

To find more details on how to use TQ1 admin, click [here](docs/admin.md)

If you are having troubles and want to view our FAQ, click [here](docs/FAQ.md)

## TQ1 basic flow

The Mobile SDKs will send all information needed to the server, while the admin is used to create, manage and view results of  campaigns.

The basic flow can be seen on the following image:

![](./images/TQ1.png)

## TQG basic flow

TQG is Taqtile's geolocation platform. It will be used to detect when user entered the desired location in order to trigger a notification.

Here is TQG basic flow:

![](./images/tqg.png)

## TQ1 + TQG

TQG can be used along with TQ1 (this is the case for most of the apps), so you can manage everything using TQ1 interface. When doing this the flow will be like this:

![](./images/tq1-tqg.png)

## Mobile SDKs documentation

[iOS](http://tq1-ios-sdk.readthedocs.io/en/master/)

[Android](http://tq1-android-sdk.readthedocs.io/en/master/)

[Windows Phone](http://tq1-wp-sdk.readthedocs.io/en/latest/)

## Public API documentation
Public API is used when you want to send pushes directly through our API, without using the admin. You can find detailed usage [here](http://docs.tq1publicapi.apiary.io/#reference/authentication).
You can also use one of our server SDKS:
[.NET](http://tq1-net-sdk.readthedocs.io/en/latest/)
[Node](https://www.npmjs.com/package/tq1-public-sdk)
