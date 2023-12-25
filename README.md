# smart-control-traffic-system
سیستم هوشمند کنترل ترافیک 
### Read Me

---

### توضیحات
این برنامه با استفاده از کتابخانه‌های `pandas`, `numpy`, `folium`, `sklearn` و `matplotlib` برای جمع‌آوری، پردازش و تحلیل داده‌های ترافیک، اجرای الگوریتم KMeans و نمایش نقشه‌ی محل تهران طراحی شده است.

### نصب موارد مورد نیاز
برای اجرای این برنامه، نیاز به نصب کتابخانه‌های زیر است:
- pandas
- numpy
- folium
- scikit-learn (sklearn)

شما می‌توانید این کتابخانه‌ها را با استفاده از `pip` نصب کنید:

```bash
pip install pandas numpy folium scikit-learn
```

### اجرای برنامه

برای اجرای برنامه، فایل `main.py` را اجرا کنید. این برنامه داده‌های ترافیک را جمع‌آوری کرده، پردازش می‌کند، الگوریتم KMeans را اجرا می‌کند و خروجی نهایی را در فایل `output.csv` ذخیره می‌کند.

```bash
python main.py
```

برای اجرای برنامه، فایل ورودی `input.csv` در مسیر `data/input.csv` وجود داشته باشد. همچنین، فایل خروجی نهایی به نام `output.csv` در مسیر `data/output.csv` ذخیره خواهد شد. همچنین، یک فایل نقشه به نام `Tehran_Map.html` در همان پوشه که شامل نقشه محل تهران است، ذخیره خواهد شد.

### موارد توجه
- پیشنهاد می‌شود که داده‌های مورد نیاز (مانند `input.csv`) را قبل از اجرای برنامه در مسیر مناسب قرار دهید.
- توجه داشته باشید که این برنامه برای تحلیل و پردازش داده‌های ترافیک استفاده می‌شود و ممکن است نیاز به تغییرات در کد منبع داشته باشد بر اساس نیازهای خاص.
- 
  گروه NE : علی شمس / حسین پاتیمار
  منتور پروژه : امیر صدرا نام آور
  استاد راهنما : دکتر مهدی اسلامی 
---
برای سوالات و اطلاعات بیشتر، با(hsyngzwz@gmail.com, alishmas8309@gmail.com) تماس بگیرید.
