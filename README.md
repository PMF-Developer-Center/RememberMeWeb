PSL Mobile Foundation
===
## RememberMe
A sample application demonstrating use of the CredentialsValidation Security Check.

### Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/authentication-and-security/credentials-validation/

### Usage

1. Use either Maven, MobileFoundation CLI or your IDE of choice to [build and deploy the available `ResourceAdapter` and `PinCodeAttempts` adapters](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/adapters/creating-adapters/).

 The PinCodeAttempts Security Check adapter can be found here

2. From a command-line window, navigate to the project's root folder and run the command: `mfpdev app register`.

3. You can either set-up a [Web development environment] (https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/setting-up-your-development-environment/web-development-environment) that fits your needs, or use the provided Node.js-based reverse proxy.

#### WebSphere Liberty or Node.js
Follow the [Setting up the Web development environment](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/setting-up-your-development-environment/web-development-environment) tutorial.

#### Using the provided Node.js-based reverse proxy
- Make sure you have Node.js installed.
- Navigate to the sample's root folder and run the command: `npm install` followed by: `npm start`.

3. In the MobileFoundation Console → PinCodeWeb → Security, map the `accessRestricted` scope to the `PinCodeAttempts` security check.
4. In a browser, load the URL [http://localhost:9081/sampleapp](http://localhost:9081/sampleapp).

### Supported Levels
PSL Mobile Foundation 9.0

### Third Party
This sample makes use of:

* Nodejs to load RequireJS
* RequireJS to load the MobileFoundation SDK