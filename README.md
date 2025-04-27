# Power BI Sales Dashboard 📊

Bu layihə satış məlumatlarını analiz etmək və vizuallaşdırmaq üçün Power BI istifadə edilərək hazırlanmışdır. Dashboard satış performansını izləməyə, məhsul və müştəri analizləri aparmağa kömək edir.

## 🔥 Əsas Xüsusiyyətlər
- Ümumi satışlar, gəlir və sifariş sayı
- Satışların zaman üzrə trend analizi
- Məhsul kateqoriyası və fərdi məhsullar üzrə satışların vizuallaşdırılması
- Regionlara görə satışların paylanması
- Dinamik filtrlər və slicerlərlə interaktiv təhlil imkanı
## 🧠 İstifadə Edilən DAX Formulları
- Tarix = CALENDAR(MIN(
    'Əsas data'[Order Date]),
    MAX('Əsas data'[Ship Date])
    )
-Sales(Furniture) = CALCULATE(
        SUM(
            'Əsas data'[Sales]),
            'Əsas data'[Category]="Furniture"
            )

## 📂 İstifadə Qaydası
1. [Power BI Desktop](https://powerbi.microsoft.com/) proqramını kompüterinizə yükləyin.
2. Bu repository-dən `.pbix` faylını yükləyin.
3. Faylı Power BI Desktop-da açın.
4. Dashboardu araşdıraraq satış məlumatlarını interaktiv analiz edin.

## 🛠 İstifadə Edilən Texnologiyalar
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling
- Vizuallaşdırma texnikaları

## 📈 Gələcəkdə Planlaşdırılan Yeniliklər
- Satış proqnozlaşdırılması (Forecasting)
- ROI (Investment Gəliri) analizləri
- İnsan Resursları analizi
- RFM analizi
- İstifadəçi dostu daha çox interaktiv filtrelər

## 📬 Əlaqə
Əgər suallarınız varsa və ya təkliflər etmək istəyirsinizsə, mənimlə əlaqə saxlaya bilərsiniz:  
[GitHub Profilim](https://github.com/hakimnadiyev)
[linkedin Profilim]((https://www.linkedin.com/in/hakim-nadiyev-80841334a/))
