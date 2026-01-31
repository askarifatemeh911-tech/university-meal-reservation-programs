```mermaid
classDiagram
    class User {
        +String name
        +String email
        +String password
        +login()
        +register()
    }

    class Restaurant {
        +String name
        +String location
        +addMenuItem()
    }

    class MenuItem {
        +String title
        +float price
        +description
    }

    class Reservation {
        +int reservationId
        +Date date
        +int numberOfPeople
        +createReservation()
        +cancelReservation()
    }

    class Order {
        +int orderId
        +Date orderDate
        +calculateTotal()
        +addMenuItem()
    }

    User "1" --> "many" Reservation : makes
    User "1" --> "many" Order : places
    Restaurant "1" --> "many" MenuItem : offers
    Reservation "1" --> "1" Restaurant : booked at
    Order "1" --> "many" MenuItem : includes
