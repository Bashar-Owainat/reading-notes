# Http cookies

## What is an Http cookie?
It is a small set of data sent by a server to a user's web browser. The cookie could be saved by the browser and sent back to the same server with subsequent requests.

## Give three uses for cookies:
-	Session management: Logins, shopping carts, game scores, and everything else the server needs to remember are all stored on the server.
-	Personalization: Preferences, themes, and other options are available to users.
-	Tracking: Observing and analyzing user behavior

## Were cookies used for general client-side storage? And is there an alternative for them now?
Previously, cookies were utilized for generic client-side storage. While this made sense when it was the only way to store data on the client, current storage APIs are now preferred. Because cookies are delivered with every request, they might degrade performance (especially for mobile data connections)

## Is there a restriction for sending a cookie?
You can set an expiration date or time period after which the cookie will no longer be transmitted.

## What other restrictions can be applied when dealing with cookies?
Additional restrictions to a specified domain and path can be applied to limit where the cookie is transmitted.
