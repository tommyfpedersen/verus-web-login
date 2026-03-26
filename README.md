## Introduction

Add Verus Login to your website and let users use Verus Mobile to login into your site.
A simple Verus Web Login example using vanilla javascript.

## Requirements

1. Access to a running Verus Login Server or run your own -> https://github.com/tommyfpedersen/verus-login-server

To make a valid login with mobile phone the Verus Login Server needs to be deployed on a public server or tunneled locally with port forward (visual code) or use grok for complete access. Localhost will not work.

2. Verus Mobile on your phone - find more information here: https://verus.io/wallet.

3. A VerusId to test with - can be created in Verus Desktop App or Verus CLI - find more information here: https://verus.io/wallet.

## Setup

In config.js set the values to where the Verus Login Server is hosted.

VERUS_LOGIN_SERVER_API=http://192.168.1.1:8000
VERUS_LOGIN_SERVER_WS=ws://192.168.1.1:8000

## How to run

run index.html with e.g Live Server in Visual Code (Extension)
