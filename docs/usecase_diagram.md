# Use Case Diagram - سیستم رزرو غذای دانشگاه

```mermaid
actor دانشجو
actor مدیر

usecase "ورود / ثبت‌نام" as UC1
usecase "مشاهده پیشرفت پروژه" as UC2
usecase "ایجاد تسک" as UC3
usecase "مشاهده تسک‌ها" as UC4
usecase "تعیین وضعیت تسک" as UC5
usecase "ثبت رزرو غذا" as UC6
usecase "لغو / تغییر رزرو" as UC7
usecase "پرداخت آنلاین" as UC8

دانشجو --> UC1
دانشجو --> UC2
دانشجو --> UC3
دانشجو --> UC4
