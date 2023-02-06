# CodeIgniter 4 Stripe Payment Gateway Integration Application 

## About project
The payment gateway is one of the most important parts of an e-commerce site or any app that requires payment processing. One of the most popular payment processing platforms is stripe. Stripe has been one of the most chosen payment platforms for its simple integration and fast account setup. We will create a Charge in Stripe API using a token in this repo. 

## project flow
- [x] Step 1: Create Codeigniter Project
- [x] Step 2: Add Stripe PHP Library
- [x] Step 3: Get Stripe API key and Secret
- [x] Step 4: Set Up Controller
- [x] Step 5: Add Routes
- [x] Step 6: Set Up View
- [x] Step 7: Test Codeigniter Stripe App

## Test card
Name	Number	Brand	CVC	Expiry	Date
Test	4242 4242 4242 4242	Visa	456	12/25	2025

<!-- ![alt text](https://github.com/BrianNyaberi/MERN/blob/main/mern.png?raw=true) -->

## Installation & updates


## Setup

Copy `env` to `.env` and tailor for your app, specifically the baseURL
and any database settings.

## Important Change with index.php

`index.php` is no longer in the root of the project! It has been moved inside the *public* folder,
for better security and separation of components.

This means that you should configure your web server to "point" to your project's *public* folder, and
not to the project root. A better practice would be to configure a virtual host to point there. A poor practice would be to point your web server to the project root and expect to enter *public/...*, as the rest of your logic and the
framework are exposed.

**Please** read the user guide for a better explanation of how CI4 works!

## Server Requirements

PHP version 7.4 or higher is required, with the following extensions installed:

- [intl](http://php.net/manual/en/intl.requirements.php)
- [mbstring](http://php.net/manual/en/mbstring.installation.php)

Additionally, make sure that the following extensions are enabled in your PHP:

- json (enabled by default - don't turn it off)
- [mysqlnd](http://php.net/manual/en/mysqlnd.install.php) if you plan to use MySQL
- [libcurl](http://php.net/manual/en/curl.requirements.php) if you plan to use the HTTP\CURLRequest library
