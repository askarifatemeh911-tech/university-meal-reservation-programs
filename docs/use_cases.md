```mermaid
%% Use Case Diagram for University Meal Reservation System
flowchart LR

  %% ---------- Actors ----------
  student(["👨‍🎓 دانشجو"])
  admin(["🛠 مدیر سیستم"])

  %% ---------- Use Cases ----------
  UC_ViewMenu(["📋 مشاهده منوی غذا"])
  UC_ReserveMeal(["🍽️ رزرو غذا"])
  UC_CancelReservation(["❌ لغو رزرو"])
  UC_ViewHistory(["📅 مشاهده تاریخچه رزرو"])
  UC_Login(["🔐 ورود به سیستم"])

  UC_ManageMeals(["📦 مدیریت منوی غذا"])
  UC_ManageUsers(["👥 مدیریت کاربران"])
  UC_ViewReports(["📊 گزارش‌گیری"])

  %% ---------- Student Relations ----------
  student --> UC_Login
  student --> UC_ViewMenu
  student --> UC_ReserveMeal
  student --> UC_CancelReservation
  student --> UC_ViewHistory

  %% ---------- Admin Relations ----------
  admin --> UC_Login
  admin --> UC_ManageMeals
  admin --> UC_ManageUsers
  admin --> UC_ViewReports

  %% ---------- Styles ----------
  classDef actor fill:#e8f7

