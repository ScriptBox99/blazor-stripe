# Blazor and Stripe
This sample project was created to demonstrate how to integrate [Stripe](https://stripe.com/) payments with your Blazor web app. It was created by [Bradley Wells](https://wellsb.com/csharp/).  Use the included samples as guides for monetizing your own Blazor applications.

The solution includes a page for integrating and verifying connected Stripe accounts using Connect Express. Stripe Connect can be used for issuing payouts to your partners. It includes a page for adding Stripe Customers and linking credit card information to a given customer. This can be used for receiving payments from your customers. It also includes a webhooks receiver for responding to Stripe events related to your customer or connected accounts. This allows your app to perform actions such as verifying payment info when it has been changed, sending reminder emails when a payment method is about to expire, and so forth.

This project is accompanied by several blog posts describing the various components.
* Part 1: [Create a Stripe Webhooks Receiver with .NET](https://wellsb.com/csharp/aspnet/stripe-net-create-stripe-webhooks-receiver/)
* Part 2: [Add Stripe Connect Express Account with Blazor](https://wellsb.com/csharp/aspnet/stripe-connect-express-and-blazor/)
* Part 3: [Save Stripe Customer Credit Card Info](https://wellsb.com/csharp/aspnet/stripe-customer-credit-card-payment-with-blazor/)
