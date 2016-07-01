# Getting Started with Payeezy
Using below listed steps, you can easily integrate your mobile/web payment application with Payeezy APIs 
And go LIVE!
* LITE - REGISTRATION  
* CREATE AN API
* BUILD AND TEST YOUR INTEGRATION
* GET CERTIFIED
* ADD MERCHANTS 
* GO LIVE!

# LITE Registration
Sign up for a free developer account with LITE Registration. All you need is your First name, Last name and a valid email address. Navigate to developer portal https://developer.payeezy.com/ from your browser and click on CREATE ACCOUNT.
c
Note: Portal registration requires a valid e-mail address. Once registered, your email address cannot be changed in future. All e-mails from the system will be sent to this registered email address. The e-mail address will not be made public and will only be used if you wish to receive notifications by e-mail. After you provide registration information an email is sent to you with further instructions to activate your account.

# CREATE AN API
Think of this as a unique app name that is used to identify your application. This is unrelated to the name you would use on Apple’s App Store (if you are integrating with apple pay/iOS) but it can be the same. 

* Login to your Payeezy developer account and navigate to the "APIs" page.
* Click the “+ ADD A NEW API” button. 
* On the next screen you name your application. If the API is only for testing, choose "Sandbox". If you plan to use the API in the production environment, choose "Live" as well.
* Click on the API you just created. You will see your API key and API secret. These are header parameter values that uniquely identify your transactions associated with all API calls.

# BUILD AND TEST YOUR INTEGRATION
We provide a free testing environment to test your app in the SANDBOX region. To integrate and test your application all you need is 
* Merchant token
* API Key
* API Secret
* JS_Security_Key (Only required for when using the tokenization API)
* TA_TOKEN (Only required For US domiciled merchants when using the tokenization API)
* CSR or public key (only required for mobile wallet integration)

The Merchant token and JS_Security_key are available from the "Merchants" page in your developer account. These values are unique for each merchant. For testing, we have made available a First Data owned demo US gateway account called "Acme Sock". You may choose to use this or connect to your own US demo account or non-US demo account by clicking on the "Add a demo account" button. Follow the instructions on how to add your demo account or how to sign up for a demo account. Once you add your demo account, you should see it listed in the Merchants list under "Sandbox" and you should also see the merchant token and js_security_key pertaining to that account. 

The TA_TOKEN is "NOIW" for the sandbox merchant. For live processing, the TA_TOKEN will be available from [Payeezy Gateway terminal] (https://globalgatewaye4.firstdata.com/terminal).
The API key and API secret are created by you and are available in the "APIs" page.
The CSR or public key are created by you and are available in the "CERTS" page.

Select one of the Payeezy integration methods available from [Integrations page] (https://developer.payeezy.com/select-your-integration-method)

To test and integrate your payment application with Payeezy CERT environment use following URL: [https://api-cert.payeezy.com/v1/]
(https://api-cert.payeezy.com/v1/).

# Get Certified (Developer’s certification)
In order to add Merchants and Go-Live with Payeezy, you need to get certified as a Payeezy Certified Developer. Certification involves:
1. Completing a full registration
2. Submitting a sample payload as a valid JSON Purchase transaction in SANDBOX region. 

JSON request will be tested against Payeezy Cert/Sandbox environment. After you click on the certify button, JSON response and response message will be provided below certify button.  

You will be certified after submitting the CERTIFICATION form. 


# Add Merchant(s)
Once your certification is complete, developer portal will automatically redirect to “Add Merchant” page. Click on "Live" and then click on "Add a merchant". If you are adding a merchant who already has a merchant account with First Data, select "Add your existing merchant account" and follow the instructions on the screen. If the merchant does not have a First Data merchant account and needs to apply for one, select "Sign up for a merchant account" and follow the instructions. 
If for any reason, you are unable to add your merchant account, email payeezyboarding@firstdata.com with the Merchant ID (or storeID), DBA name and developer account email address. We will add the merchant account to your developer account manually and send you a notification. Use the "Add merchant" form only if the merchant needs to apply for a new merchant account with First Data.

# GO LIVE!
* Replace Sandbox URL with live environment URL: https://api.payeezy.com/v1/transactions
* Replace Sandbox merchant token with live merchant token.
* Replace Sandbox JS_Security_key with live JS_Security_key.
* Ensure that API key and API secret are enabled for live processing.
* Replace TA_TOKEN (if used) with the live TA_TOKEN available in [Payeezy Gateway terminal] (https://globalgatewaye4.firstdata.com/terminal)
* Use live certificates for mobile wallet integrations. 


# Payeezy Support
For Payeezy Support related query, send email to our support team at support@payeezy.com or call us 1.855.799.0790 for personal support in real time.
