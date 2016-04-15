## Events file

### Events definition

Events are sent from the app to our server and are recorded once received. Some events examples are *Page views*, *Login done* and *Payment conclusion*. From events information you can gather information regarding your app usage.

### File structure

The events file is a `zip` file that contains one UTF-8 encoded [CSV](https://tools.ietf.org/html/rfc4180) file per event type. For example, if your app is sending events for *Payment conclusion* and *Element interaction*, there will be 2 files which names will be the events' one.

The CSV columns will represent the event segments and we associate the segments if they arrive on the same request on our server, so if there are lines with just one value, that's because your app is sending the segments separately and we aren't able to group them.

The value types will vary according to what you send to us.

The events file is generated everyday and contains data for the past month.
