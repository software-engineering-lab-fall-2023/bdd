# BDD

- Pouya Esmaili - 98105581
- Nazanin Azarian - 98105568

در اجرای Scenario Outline تست دوم به مشکل undefined بر می‌خورد زیرا در آن کاراکتر - وجود دارد که در regex مشخص شده در Stepdefs وجود ندارد. برای حال این مشکل تنها کافیست در regex مربوطه کاراکتر منفی را نیز پیش‌بینی کرده و به صورت optional آن را قرار دهیم.