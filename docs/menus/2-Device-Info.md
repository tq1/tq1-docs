## Device Information File

The device info file will be a `CSV` with the following format:

`did,push_enable,platform,custom_data1,custom_data2`

- did: The device ID
- push_enable: Can be true or false, tells if the user has the push enabled on the device settings
- platform: Android, iOS or Windows Phone
- custom data: Following the previous information, there will be all custom data keys for the application

This file is generated at everyday.
