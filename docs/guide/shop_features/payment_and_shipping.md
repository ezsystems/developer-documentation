# Payment and shipping [[% include 'snippets/commerce_badge.md' %]]

Payment is based on a standard Symfony bundle. 
By default, the invoice payment is available.

You can also integrate other payment providers, such as [PayPal](../payment/paypal.md)

The payment and shipping methods can be enabled or disabled per SiteAccess.

## Shipping costs

[[= product_name =]] offers a flexible way to define shipping costs, if they are not set in the ERP system.

Shipping costs can be set up per:

- currency
- shipping method
- country
- state
- ZIP code (e.g. for exceptions such as delivery to islands)
- size of the basket (including free of freight rules)

If no shipping costs are defined for a given country, shipping method, currency and value of goods, a fallback cost from the configuration is used.
