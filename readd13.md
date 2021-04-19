


## HISTORY OF LOCAL STORAGE :


userData allows web pages to store up to 64 KB of data per domain


Flash objects to store up to 100 KB of data per domain.

HTML5 set out to solve: to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.

## INTRODUCING HTML5 STORAGE

It’s a way for web pages to store named key/value pairs locally, within the client web browser.  the data will be saved even if you exit the browser.

## USING HTML5 STORAGE

key/value pairs.,You store data based on a named key, then you can retrieve that data with the same key. the key is astring and the data can be anything and you can call it with the key name ,non-existent key will return null

TRACKING CHANGES TO THE HTML5 STORAGE AREA

The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. and it is supported everywhere the localStorage object is supported,

## LIMITATIONS IN CURRENT BROWSERS

“5 megabytes” is how much storage space each origin gets by default. so if you use float each inger moves will add and stored as chachters.

“QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes. and you cant ask the user for more storage .











