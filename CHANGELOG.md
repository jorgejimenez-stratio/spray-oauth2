# Changelog

## 0.3.8 (Upcoming)

* [GS-1708] Flag httpOnly in user cookie set to true

## 0.3.7 (November 14, 2019)

* [GS-1658] GosecManagement oAuth secret is leaked if last login?code=ST-XXXX request is repeated

## 0.3.6 (March 26, 2019)

* [SECTY-989] Throw exception when sso returns some error

## 0.3.5 (October 18, 2018)

* Set scala version to 2.11 and do not use crossbuild plugin

## 0.3.4 (October 18, 2018)

* Use proper version for crossbuild plugin
 
## 0.3.3 (October 17, 2018)

 * Improved logs info 

## 0.3.2 (February 22, 2017)

* Fixed creation of expired sessions

## 0.3.1 (February 17, 2017)

* Handle crossbuilds properly

## 0.3.0 (February 17, 2017)

* Clean and remove invalid sessions

## 0.2.0 (March 28, 2016)

* Authorize directive for reject request without login
* Now role field can be configured from application.conf

## 0.1.0 (March 11, 2016)

* Initial version of a spray client, which supports OAuth 2.0 protocol.
