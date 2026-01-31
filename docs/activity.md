flowchart TD
    A[Start] --> B{Login?}
    B -- Yes --> C[Dashboard]
    B -- No --> D[Register]
    D --> C
    C --> E[Create Repository]
    E --> F[End]

