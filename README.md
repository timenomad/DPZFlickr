DPZFlickr (timenomad's fork)
=========

Forked from https://github.com/timenomad/DPZFlickr

The additions are as follows:
* Add option to set access token upon object instantiation (example: $api->setAccessToken(*access token string*))
* Add option to get OAuth URL instead of an HTTP redirect (example: $api->authenticate('read', $is_redirect = false))
* Fix composer.json ext-curl demanding version '0'
