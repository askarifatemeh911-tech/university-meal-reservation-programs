```mermaid
stateDiagram-v2
    [*] --> BrowsingMenu

    BrowsingMenu --> SelectingItems : user selects menu items
    SelectingItems --> ReviewingOrder : user reviews order
    ReviewingOrder --> PaymentPending : proceeds to payment
    PaymentPending --> PaymentConfirmed : payment successful
    PaymentPending --> OrderCancelled : payment failed or cancelled

    PaymentConfirmed --> OrderPrepared : restaurant prepares order
    OrderPrepared --> OrderDelivered : delivery completed
    OrderDelivered --> [*]

    OrderCancelled --> [*]

