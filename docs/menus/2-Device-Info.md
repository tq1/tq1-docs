## Device Information File

### Custom data definition

Custom data are the fields used to filter when sending pushes. Once the app sends the custom data to TQ1, it's key becomes available so you can filter using it. Knowing the custom data values is important so you'll be able to filter the push notification more efficiently.

### File structure

The device info file will be an UTF-8 encoded [CSV](https://tools.ietf.org/html/rfc4180) with the following format:

`did,push_enable,platform,custom_data1,custom_data2`

- did: The device ID
  - Type: String
- push_enable: Can be true or false, tells if the user has the push enabled on the device settings
  - Type: String
- platform: *Android*, *iOS* or *Windows Phone*
  - Type: String
- custom data: Following the previous information, there will be all custom data keys for the application
  - Type: String

This file is generated at everyday.
