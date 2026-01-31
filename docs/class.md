```mermaid
classDiagram
    class User {
        +String name
        +String email
        +login()
    }

    class Order {
        +int orderId
        +Date date
        +calculateTotal()
    }

    class Product {
        +String title
        +float price
    }

    User "1" --> "many" Order
    Order "many" --> "many" Product

