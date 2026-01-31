```mermaid
flowchart TD
    A([Start]) --> B[Browse Menu]
    B --> C{Select Items?}
    C -->|Yes| D[Add Items to Cart]
    C -->|No| E([End])

    D --> F[Review Order]
    F --> G{Proceed to Payment?}
    G -->|Yes| H[Enter Payment Info]
    G -->|No| E

    H --> I{Payment Successful?}
    I -->|Yes| J[Order Confirmed]
    I -->|No| K[Order Cancelled]

    J --> L[Restaurant Prepares Order]
    L --> M[Order Delivered]
    M --> E
    K --> E


