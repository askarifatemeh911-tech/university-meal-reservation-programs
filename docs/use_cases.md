```mermaid
flowchart LR

  %% ---------- Styles ----------
  classDef page fill:#fff7e6,stroke:#e67e22,stroke-width:2px,color:#000,rx:12,ry:12;
  classDef action fill:#e8f7ff,stroke:#3498db,stroke-width:2px,color:#000,rx:12,ry:12;
  classDef system fill:#f0e9ff,stroke:#8e44ad,stroke-width:2px,color:#000,rx:12,ry:12;

  %% ---------- Pages ----------
  Home["🏠 Home (صفحه اصلی)"]:::page
  Menu["📋 Menu (منو)"]:::page
  Food["🍽️ Food Item (جزئیات غذا)"]:::page
  Cart["🛒 Cart (سبد خرید)"]:::page
  Checkout["💳 Checkout (پرداخت)"]:::page
  Confirm["✅ Order Confirm"]:::page
  Account["👤 User Account"]:::page

  %% ---------- System ----------
  Admin["🛠 Admin Dashboard"]:::system
  API["🔌 Backend API"]:::system

  %% ---------- Flow ----------
  Home --> Menu
  Menu --> Food
  Food -->|Add| Cart
  Cart --> Checkout
  Checkout --> Confirm

  Account -->|View Orders| Confirm
  Admin -->|Manage Menu| Menu

  API -->|Get Foods| Menu
  API -->|Send Order| Checkout
