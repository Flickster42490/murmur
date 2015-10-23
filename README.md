# murmur
*check out murmur at http://murmur2.xyz* 

Murmur is a web app with anonymity at its core. Its geo-fencing capabilities allow the users to choose two different levels of anonymity. Its automatic moderator function sanitizes the message board from racism, sexism, and general inappropriateness. Its hashtag search feature allows the user to quickly pull up relevant topics. 

This web app uses React to perform quick client side rendering based on various user events. For example, typing in a hashtag and clicking the search button will force the client to filter results and render only the appropriate hashtagged messages. 

The users are able to select different levels of anonymity if they click the 'My City' button. This enables HTML5 geolocation and through Google Map API's reverse geocoding, the user is taken to the city Mumur from where they are reading and posting. This funciton also allows the users to provide more relevance to their message. For example, people in Murmur San Francisco are more likely to respond to a comment made about 49er's quarterback, Colin Kapernick's recent bad plays.

Murmur is built with React, Node.js, Express.js, and Firebase. The native iOS prototype of Murmur is read-only and is built with React Native. The reverse geocoding was done through Google Map's API and JWT tokens were used for authentication.

