flowchart TD
    A((Start))
    B{Login?}
    C[Register]
    D[Dashboard]
    E((End))

    A --> B
    B -- No --> C
    C --> D
    B -- Yes --> D
    D --> E
