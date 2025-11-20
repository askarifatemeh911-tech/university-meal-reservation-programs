```mermaid
flowchart TD

  classDef page fill:#ffefd5,stroke:#e67e22,stroke-width:2px,color:#000,rx:12,ry:12;
  classDef system fill:#eaf2ff,stroke:#2980b9,stroke-width:2px,color:#000,rx:12,ry:12;

  Home["🏠 Home / صفحه‌ٔ اصلی"]:::page
  Menu["📋 Menu / منو"]:::page
  Item["🍽️ Food Item / صفحهٔ غذا"]:::page
  Cart["🛒 Cart / سبد خرید"]:::page
  Checkout["💳 Checkout / پرداخت"]:::page
  OrderConfirm["✅ Order Confirm / تایید سفارش"]:::page
  UserAcc["👤 User Account / حساب کاربری"]:::page

  Admin["🛠 Admin Dashboard"]:::system
  API["🔌 Backend API"]:::system

  Home -->|browse| Menu
  Menu -->|view item| Item
  Item -->|add| Cart
  Cart --> Checkout
  Checkout --> OrderConfirm
  UserAcc -->|view orders| OrderConfirm
  Admin -->|manage menu| Menu
  API -->|serves data| Menu
  API -->|process| Checkout



