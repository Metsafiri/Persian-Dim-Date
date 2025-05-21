# Persian-Dim-Date
Power BI Dim_Date with lag columns (DayLag, WeekLag, MonthLag, YearLag) in Power Query M for easy time intelligence (MTD, YTD, MoM, YoY, WoW). Includes a ready .pbix file—just add your datasets (except Dim_Date) and start analyzing period-over-period trends quickly.

# Power BI Dim_Date with Lag Columns

This repository contains the Power Query M code for creating a comprehensive `Dim_Date` dimension table in Power BI. The `Dim_Date` includes additional calculated columns such as `DayLag`, `WeekLag`, `MonthLag`, and `YearLag`, designed to facilitate time intelligence calculations.

## Features

- Date dimension with full date attributes (year, quarter, month, day, weekday, etc.)
- Lag columns for:
  - **DayLag**: Number of days lag from a reference date
  - **WeekLag**: Number of weeks lag for period-over-period comparisons
  - **MonthLag**: Month lag for month-over-month and same period last month calculations
  - **YearLag**: Year lag for year-over-year and same period last year analysis
- Enables easy calculation of:
  - Month-to-date (MTD)
  - Year-to-date (YTD)
  - Same period last month/week/year
  - Month-over-month (MoM), Year-over-year (YoY), Week-over-week (WoW) comparisons

## Usage

Just open the provided `.pbix` file, add your datasets except the `Dim_Date` table, and enjoy easy time intelligence calculations.

## Why Use Lag Columns?

Lag columns enable faster and simpler DAX measures when calculating period comparisons like MoM, YoY, MTD, YTD, and period-over-period analysis without complex time calculations in DAX.

## Contributing

Feel free to fork and contribute improvements, fixes, or additional features by submitting a pull request.

## License

This project is licensed under the MIT License.

---

# جدول تاریخ (Dim_Date) در پاور بی‌آی با ستون‌های فاصله زمانی

این مخزن شامل کد M در Power Query برای ایجاد یک جدول تاریخ کامل (`Dim_Date`) در پاور بی‌آی می‌باشد. این جدول شامل ستون‌های محاسبه شده‌ای مانند `DayLag`، `WeekLag`، `MonthLag` و `YearLag` است که محاسبات هوش زمانی را آسان‌تر می‌سازد.

## ویژگی‌ها

- جدول تاریخ با ویژگی‌های کامل شامل سال، فصل، ماه، روز، روز هفته و غیره  
- ستون‌های فاصله زمانی:
  - **DayLag**: تعداد روزهای فاصله از یک تاریخ مرجع  
  - **WeekLag**: تعداد هفته‌های فاصله برای مقایسه دوره به دوره  
  - **MonthLag**: فاصله ماه برای محاسبات ماه به ماه و دوره مشابه ماه قبل  
  - **YearLag**: فاصله سال برای تحلیل سال به سال و دوره مشابه سال قبل  
- قادر به انجام محاسبات ساده و سریع مانند:
  - ماه به تاریخ (MTD)  
  - سال به تاریخ (YTD)  
  - دوره مشابه ماه قبل/هفته قبل/سال قبل  
  - مقایسه ماه به ماه (MoM)، سال به سال (YoY)، هفته به هفته (WoW)

## نحوه استفاده

کافیست فایل `.pbix` ارائه شده را باز کنید، داده‌های خود را به جز جدول `Dim_Date` اضافه کنید و از محاسبات هوش زمانی ساده لذت ببرید.

## چرا از ستون‌های فاصله زمانی استفاده کنیم؟

ستون‌های فاصله زمانی باعث ساده‌تر و سریع‌تر شدن ساخت معیارهای DAX می‌شوند و محاسبات مقایسه دوره‌ای مانند MoM، YoY، MTD و YTD را بدون نیاز به محاسبات زمان پیچیده در DAX امکان‌پذیر می‌کنند.

## همکاری و مشارکت

شما می‌توانید این مخزن را فورک کرده و بهبودها، رفع اشکال یا ویژگی‌های جدید را از طریق ارسال pull request اضافه کنید.

## مجوز

این پروژه تحت مجوز MIT منتشر شده است.

---

Created by [Your Name]  
