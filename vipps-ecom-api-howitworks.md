# Vipps eCommerce API: How It Works

This is how payment with Vipps eCommerce works.

For technical documentation go to: [Vipps eCom API](https://github.com/vippsas/vipps-ecom-api),
with Swagger specifications, Postman collections, example code, integration
checklist and the [FAQ](vipps-ecom-api-faq.md).

## The ecommerce payment process

![Ecom process](images/vipps-ecom-process.png)


## 1. Pay with Vipps

The user chooses “Pay with Vipps”, either in the checkout, or on the product page (express checkout) of a merchant’s website or app.

![Pay with Vipps](images/vipps-ecom-step1.png)

## 2. The Vipps landing page

If the payment was started on a desktop device the user will be sent to the Vipps landing page.
The user confirms their number, and is prompted to log in to Vipps. 

If the payment was started from a mobile device, the app wil automatically switch over to Vipps.

![Vipps landing page](images/vipps-ecom-step2.png)

## 3. Confirm payment in Vipps

The user receives a push notification on their phone. They log in to Vipps, and confirm the payment. The payment is reserved and the user gets a receipt of the successful payment

For express checkout they also have to choose a shipping cost alternative.

![Confirm payment](images/vipps-ecom-step3.png)

## 4. Order Confirmation

The user is redirected back to the merchant’s store, and the order is confirmed.

![Order confirmation](images/vipps-ecom-step4.png)

## 5. Completing the order and shipping

The merchant completes the order, and ships the order to the customer.


## 6. Money in the bank

The payment is transferred to the merchant’s account. This may take 2-3 days depending on your bank.

## Great! Now you know how the payment process works.

Take a look at the technical documentation in the [Vipps eCommerce API Guide](https://github.com/vippsas/vipps-ecom-api/blob/master/vipps-ecom-api.md)


## Questions?

We're always happy to help with code or other questions you might have!
Please create an [issue](https://github.com/vippsas/vipps-ecom-api/issues),
a [pull request](https://github.com/vippsas/vipps-ecom-api/pulls),
or [contact us](https://github.com/vippsas/vipps-developers/blob/master/contact.md).