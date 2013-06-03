Othenticator 
=================
Othenticator is an oAuth authenticator that uses oauth apis of services such as facebook and google.Other services can also be added. Order can be assigned as to which services should be tried first for checking session.

*Base SDK for facebook and google are included in base_sdk folder*

*requires curl extension to be installed in PHP*

## Pre-requisites 
Othenticator requires oauth tokens from services
> For facebook authentication , create an app with facebook app  dashboard : https://developers.facebook.com/apps

> For google authentication visit : https://code.google.com/apis/console/?
*Issue with google :  must predefine callback URL , this means auth token from google can only be used with predefined url*

## Settings
Edit and add the auth tokens received in above step in oauth_config.php.
*By default Othenticator provides access to only some resources like user name , email , display picture and unique user id , additional info can be fetched by tweaking app tokens on respective app dashboards
* Fine tuning like order of login check and other details like additional info and urls can be done in oAuthinterface.php

## Test
for testing the settings oAuthtester.php can be used

