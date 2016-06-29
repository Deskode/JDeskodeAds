JDeskodeAds
======

A jQuery plugin to get information about public videos, clients, screens and activity from the DeskodeAds API. 
Visit www.deskode.com

## Dependencies
For normal usage; jQuery 1.3 or higher.

## Usage
JDeskodeAds makes available methods for retrieving video and user information from the Ads.Deskode.com API. All the available methods are accessed from the JDeskodeAds object which is a member of the jQuery or $ object.

### Get User data
$.jdeskodeads.request(id, callback)

**Parameters**
* > request ("getClientes").
* > id string/int.
* > callback FUNC Function to call once the request has completed successfully. One parameter will be passed containing the JSON response of the request; callback(data).
