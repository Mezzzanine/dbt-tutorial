{% docs order_status %}

One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs payment_method %}

One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| credit_card    | Payed by credit card, such as Master Card, Visa  |
| bank_transfer  | Payed with bank transfer using IBAN              |
| coupon         | Payed with coupon that caustomer can get from the promotion |
| gift_card      | Payed with gift cards that customer could ahve as a gift |

{% enddocs %}