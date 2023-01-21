A smart, dynamic rate-limiting service for API gateways and high cost-per-transaction services. The rate-limiting endpoint is used
to enforce quotas and traffic shaping based on potentially multiple elements in the request--instead of rate-limiting based on simple, single API
keys as authorization tokens.

This API can be used to enforce license-based SLAs and dynamic traffic shaping in multi-tenant SaaS APIs and applications.

Some use cases are:
* Controlling high cost-per-transaction calls like Know Your Customer (KYC) verifications for each customer and/or mobile device.
* Multi-tenant API security where there are different SLAs per tenant or tenant type.
* Traffic shaping of API usage based on different aspects of a request such as IP address, application, tenant, customer, device, and/or user.
