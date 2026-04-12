# DASHBOARD DEVELOPMENT

An interactive Power BI dashboard built on a used cars dataset with 10,000 listings. Covers selling price, fuel type, transmission, and manufacture year trends.

---

## Dashboard Preview

<img width="1194" height="669" alt="Image" src="https://github.com/user-attachments/assets/0637f7ab-50bc-490f-8321-2feb913ae96f" />

---

## Dataset

10,000 rows of used car listings with columns including Car Name, Selling Price (Lakh), Present Price (Lakh), Kms Driven, Fuel Type, Seller Type, Transmission, and Year.

---

## KPI Cards

Three summary cards at the top give a quick overview:

| Metric | Value |
|---|---|
| Total cars listed | 10K |
| Average selling price | ₹2.20L |
| Average kms driven | 119,302 km |

---

## Visuals

**Cars by Fuel Type** (Donut Chart)  
Breaks down the listing share by fuel type. Petrol dominates at 85.94%, followed by Diesel at 14.04%, and CNG at just 0.02%.

**Avg Selling Price by Transmission** (Bar Chart)  
Automatic cars average ₹4.78L, more than double the ₹1.98L average for manual cars.

**Max Selling Price by Car Name** (Horizontal Bar Chart)  
Top 5 most expensive cars in the dataset:
- Land Cruiser - ₹35.00L
- Fortuner - ₹33.00L
- Innova - ₹23.00L
- Corolla Altis - ₹17.00L
- Creta - ₹12.90L

**Average Selling Price by Manufacture Year** (Line Chart)  
Shows how average selling price shifts across manufacture years (2000–2020). Prices dip around 2008-2010 and climb noticeably from 2015 onward, peaking at ₹4.3L for 2020 models.

---

## Filters / Slicers

Three slicers on the left panel let users slice the data interactively:

- **Fuel Type** — CNG / Diesel / Petrol
- **Seller Type** — Dealer / Individual
- **Transmission** — Automatic / Manual

---

## Tool Used

- Power BI Desktop
