# Use Case Diagram - سیستم رزرو غذای دانشگاه

```mermaid
actor دانشجو
actor مدیر

usecase "ورود / ثبت‌نام" as UC1
usecase "مشاهده منو و ظرفیت‌ها" as UC2
usecase "رزرو غذا" as UC3
usecase "لغو / تغییر رزرو" as UC4
usecase "پرداخت آنلاین" as UC5
usecase "مدیریت منو" as UC6
usecase "مشاهده گزارش‌ها" as UC7

دانشجو --> UC1
دانشجو --> UC2
دانشجو --> UC3
دانشجو --> UC4
دانشجو --> UC5

مدیر --> UC1
مدیر --> UC6
مدیر --> UC7
