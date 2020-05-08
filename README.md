# Razorpay Test App for .NET-MVC

This app uses nuget package based sdk integration, and add the required version of dll in your project reference.

# Steps for Integration:
1. Make a checkout form using our Checkout Integration
2. Accept the razorpay_payment_id parameter in the form submission
3. Run the capture code to capture the payment

Please make sure you do the following while using this:
1. Edit the key inside Orders.cshtml
2. Edit the keyId/keySecret in OrderController and ChargeController
