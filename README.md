# randogram
A service that gathers content from a published Livefyre collection and provides an API to access such content in a random order.
---
## Start-up
Will take a parameter to specify the collection location by URL, URN, or possibly just ID

## API
Will provide one method, which replies with image data. Session will be monitored so that each user gets their own random order that cycles if necessary. An option may exist in the GET method that allows the caller to specify the attached image content or a rendered version of the social post.

