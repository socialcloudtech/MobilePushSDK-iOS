# ExactTarget MobilePush SDK for iOS

This is the git repository for the ET MobilePush SDK for iOS. 

For more information, please see [Code@ExactTarget](http://code.exacttarget.com).

## Release History

### Version 2.1.3

* Bug fixes. 

### Version 2.1.2

* Various bug fixes and enhancements. 
* Deprecated internal functionality that was no longer required. 

### Version 2.1.1

* Changes required in preparation for iOS 7 compatibilty. 

### Version 2.1.0

* OpenDirect payloads containing a full URL will automatically present themselves on app load. This functionality only works if there is no OpenDirect Delegate set. 
* Verious bug fixes and improvements. 

### Version 2.0.1

* Updated Urban Airship library to 1.4.0 to be compliant with recent Apple approval changes. 

### Version 2.0.0

* Support for Access Tokens in place of Client ID/Secret. Access Token is provided by Code@ExactTarget during app registrations. 
* Added support for Subscriber Key. 
* Added support for determining push enabled state based on the Notifications tab in Settings.
* Significantly reworked sample project to demonstrate new features and fix some bugs. 


### Version 1.1.1

* First public version!
* Support for OpenDirect, including the ExactTargetOpenDirectDelegate
* Bugfixes around timezones and GMT-0000 and attribute processing