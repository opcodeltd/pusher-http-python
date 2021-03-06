#### 1.2.2 2015-06-12

Added Wheel file publishing. No functional changes.

#### 1.2.1 2015-06-03

Added cacert.pem to the package, getting rid of errors upon SSL calls.

### 1.2.0 2015-05-29

* Renamed `URLFetchBackend` to `GAEBackend`, which specifically imports the Google App Engine urlfetch library. 
* Library creates an SSL context from certificate, addressing users receiving `InsecurePlatformWarning`s.

### 1.1.3 2015-05-12

Tightened up socket_id validation regex.

### 1.1.2 2015-05-08

Fixed oversight in socket_id validation regex.

### 1.1.1 2015-05-08

* Library now validates `socket_id` for the `trigger` method.

## 1.1.0 2015-05-07

* User can now specify a custom JSON encoder or decoder upon initializing Pusher.

#1.0.0 2015-04-25

* Python 2.6, 2.7 and 3.3 support
* Adapters for various http libraries like requests, urlfetch, aiohttp and
  tornado.
* WebHook validation
* Signature generation for socket subscriptions

0.1.0 / 2014-09-01
==================

First release
