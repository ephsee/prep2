Problem

One of the key pieces to any e-commerce site is a working checkout page. For us, this is where the user’s personal, shipping, and billing information gets tied together with their soon to be purchased order. Given the following checkout page (link), we need to plan out a solution for validating the information provided before charging the customer and submitting the order.


(Seniors only) Secondarily, we need to come up with an interface for validating coupons. In the current case, the coupon `HELLO30` can only be once per customer and only by used by new customers on their first order. In other cases, such as temporary promotions, coupons may only be able to be used a certain number of times across all customers. We need to establish the data model(s) and code interface that will enable us to validate coupons entered on the checkout page.


Key Requirements

Solution should be able to validate each of the fields on the page

Architecture should be scalable

Any API(s) should be well defined

Request/response bodies

URIs + HTTP methods

(Level II+) Coupon data model(s) for validation should be defined to cover the following cases:

Coupons can only be used a certain number of times total

Coupons can only be used a certain number of times per user

Coupons can only be used for new customers

(Senior) Coupon validation should be defined as pseudo code to account for the same cases
