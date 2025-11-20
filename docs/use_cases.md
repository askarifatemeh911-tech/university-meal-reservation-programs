```mermaid
flowchart TD
  Home["Home / صفحه‌ٔ اصلی"]
  Menu["Menu / منو"]
  Item["Food Item / صفحهٔ غذا"]
  Cart["Cart / سبد خرید"]
  Checkout["Checkout / پرداخت"]
  OrderConfirm["Order Confirm / تایید سفارش"]
  UserAcc["User Account / حساب کاربری"]
  Admin["Admin Dashboard / پنل مدیریت"]
  API["API / Backend API"]

  Home -->|browse| Menu
  Menu -->|view item| Item
  Item -->|add| Cart
  Cart --> Checkout
  Checkout --> OrderConfirm
  UserAcc -->|view orders| OrderConfirm
  Admin -->|manage menu| Menu
  API -->|serves data| Menu
  API -->|process| Checkout


