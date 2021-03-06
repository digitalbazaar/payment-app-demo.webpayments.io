# payment-app-demo.web-payments.io

A demonstration site for a W3C Web Payments Payment Application.

A live version and demo of this site can be found at [payment-app-demo.web-payments.io][].

# Core Functionality

This software enables a person to:

* Request a payment application
* Send a payment request to the payment application
* Receive a payment response

# Development

The following section explains how to setup and develop the 
payment-app-demo.web-payments.io software on a local development machine.

### Requirements

* node.js
* npm

### Configuration

The options in the `./configs/payment-app-demo.web-payments.dev.js` file can 
be tuned to your environment as needed.

## Setup

* Install the dependencies by running `npm install`
* Map the `payment-app-demo.web-payments.dev` hostname to your localhost.
  (for example, edit `/etc/hosts`) to map `payment-app-demo.web-payments.dev` 
  to `localhost`).

### Running

Run the following to start up a development server from the source directory:

    node payment-app-demo.webpayments.dev.js

To add more verbose debugging, use the `--log-level` option:

    node payment-app-demo.webpayments.dev.js --log-level debug

### Usage

Access the server at the following URL:

* http://payment-app-demo.webpayments.dev.js:53080/

[payment-app-demo.web-payments.io]: https://payment-app-demo.web-payments.io/
