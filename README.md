Opauth-Yahoo
Opauth strategy for Yahoo.com authentication.

Implemented based on http://developer.yahoo.com/oauth/guide/oauth-auth-flow.html using OAuth 1.0.

Opauth is a multi-provider authentication framework for PHP.

Getting started
Install Opauth-Yahoo:

cd path_to_opauth/Strategy
git clone git://github.com/booper/opauth-yahoo.git Yahoo
Sign Up Yahoo App and Get a Consumer Key at https://developer.apps.yahoo.com/dashboard/createKey.html

During registration, indicate the kinds of Yahoo! User data (also called Scopes) you want to access.
Later in the OAuth process, Yahoo! will ask your Users if Yahoo! should allow you to access their User data.
For more information about Scopes, see Scopes section (http://developer.yahoo.com/oauth/guide/oauth-scopes.html).
Configure Opauth-Google strategy.

Direct user to http://path_to_opauth/Yahoo to authenticate

Strategy configuration
Required parameters:

<?php
'Google' => array(
    'key' => 'Consumer Key',
    'secret' => 'Consumer Secret'
)
Optional parameters: appid ( Provide it if you have several apps in Tahoo.com)

References
Using OAuth 2.0 to Access Google APIs
Using OAuth 2.0 for Login
Using OAuth 2.0 for Web Server Applications
License
Opauth-Google is MIT Licensed
Copyright © 2013 Valerii Igumentsev  (http://facebook.com/ibooper)


