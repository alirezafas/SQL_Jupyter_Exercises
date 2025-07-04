# تمرینات SQL با Jupyter Notebook و SQLite

این ریپازیتوری شامل مجموعه‌ای از مسائل تمرینی SQL است که با استفاده از پایگاه داده SQLite در محیط Jupyter Notebook حل شده‌اند. هدف این پروژه، تقویت مهارت‌های عملی SQL و تحلیل داده با پایتون است.

---

## ابزارهای استفاده شده

* **Python:** زبان برنامه‌نویسی اصلی.
* **Jupyter Notebook:** محیط تعاملی برای نوشتن و اجرای کد.
* **SQLite3:** پایگاه داده سبک و بدون سرور.
* **Pandas:** کتابخانه پایتون برای کار با داده‌ها و نمایش نتایج SQL.

---

## ساختار پروژه

* `mydatabase.db`: فایل پایگاه داده SQLite حاوی اطلاعات Customers, Products, Orders, و OrderDetails. (این فایل بعد از اجرای کد Python ایجاد می‌شود.)
* `[نام_فایل_Jupyter_Notebook_شما].ipynb`: فایل Jupyter Notebook اصلی که شامل تعاریف جداول، وارد کردن داده‌ها، و راه‌حل مسائل SQL است. (مثلاً `Problem_Set_1.ipynb`)

---

## نحوه اجرا

برای اجرای این پروژه به صورت محلی:

1.  **گیت کلون (Clone) کن:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/SQL_Jupyter_Exercises.git](https://github.com/YourGitHubUsername/SQL_Jupyter_Exercises.git)
    ```
    (به جای `YourGitHubUsername`، نام کاربری گیت‌هاب خودت و به جای `SQL_Jupyter_Exercises`، نام ریپازیتوری خودت رو بذار.)
2.  **وارد پوشه پروژه شو:**
    ```bash
    cd SQL_Jupyter_Exercises
    ```
3.  **Jupyter Notebook رو باز کن:**
    ```bash
    jupyter notebook
    ```
4.  فایل `.ipynb` را باز کرده و سلول‌ها را به ترتیب اجرا کنید.

---

## مسائل حل شده

### مسئله 1: لیست مشتریان با نام کامل

**صورت مسئله:**
یک لیست از نام و نام خانوادگی کامل مشتریان را همراه با شهر و کشور آن‌ها به دست آورید. لیست نهایی باید بر اساس کشور (صعودی) و سپس نام خانوادگی (صعودی) مرتب شده باشد.

**کد SQL مربوطه در `[نام_فایل_Jupyter_Notebook_شما].ipynb`:**
```sql
-- این کوئری داخل فایل Jupyter Notebook شما وجود دارد
SELECT
    Country,
    City,
    LastName,
    FirstName,
    FirstName || ' ' || LastName AS FullName
FROM
    Customers
ORDER BY
    Country ASC,
    LastName ASC;
