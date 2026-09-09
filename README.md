# Myntra-Fashion-Clothing-Analysis
![Myntra Fashion & Clothing Analysis](project-preview.png)
## 📌 Project Overview

This project analyzes a large Myntra fashion and clothing dataset using Microsoft Excel.

The analysis focuses on data cleaning, discount standardization, pricing analysis, missing-value handling, product classification and lookup-based data retrieval.
## 🎯 Objectives

- 🧹 Identify and handle data-quality issues
- 🏷️ Standardize discount information
- 💰 Analyze product pricing
- 📊 Calculate business metrics
- 👕 Analyze size availability
- 🔎 Retrieve product-level information using lookup functions
## 🧹 Data Cleaning & Preparation

### 1️⃣ Duplicate Validation

Product IDs were checked for duplicate values.

**Result:** No duplicate values were found.

### 2️⃣ DiscountOffer Standardization

Inconsistent discount formats were standardized into a consistent analytical field.

### 3️⃣ Missing DiscountPrice Handling

Rows where both DiscountPrice and DiscountOffer were null were identified and DiscountPrice was filled using the average DiscountPrice of the respective category.

### 4️⃣ SizeOption Standardization

Null SizeOption values were replaced with `Not Available`.
## 📊 Business Analysis

### 1️⃣ Average Original Price for Ratings > 4

**Result:** ₹1,966.667

### 2️⃣ Products with Discount > 50%

**Result:** 221,864

### 3️⃣ Products Available in Size M

**Result:** 656
## 🔎 Data Retrieval & Lookup

### VLOOKUP

Retrieved BrandName, OriginalPrice and Ratings using Product ID.

### INDEX + MATCH

Retrieved DiscountPrice for a specific Product ID.

### Nested XLOOKUP

Used Product ID together with a selected column header to dynamically retrieve product-level information.
Product ID: 2296012
Product Column: Original Price
Product Detail: ₹1,499
## 🧮 Excel Functions Used

- IF
- AND
- COUNTIF
- AVERAGEIF
- XLOOKUP
- VLOOKUP
- INDEX
- MATCH
- SUBSTITUTE
- IFERROR
## 🛠️ Tools Used

- 📊 Microsoft Excel
- 📑 Microsoft PowerPoint
- 🐙 GitHub
## 📁 Project Files

- 📊 [Excel Analysis Workbook](https://1drv.ms/x/c/450abc30083dfbb8/IQAm1fTTfDTTSL63OJwiN7viATxGMNePeF5U6gewPwvBnUE?e=LCkXuQ)
- 📄 [Project Presentation](./Myntra_Fashion_Clothing_Analysis.pdf)
## 📌 Conclusion

The project demonstrates a structured Excel-based approach to transforming raw apparel data into standardized, analyzable information and retrieving product-level insights using lookup techniques.
