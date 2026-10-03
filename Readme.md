# 🏢 Real Estate Analytics & Business Intelligence Dashboard

[![Author](https://img.shields.io/badge/Author-Omar%20Mosaad%20Ahmed-blue.svg)](https://github.com/Omar-Mosaad91)
[![Tool](https://img.shields.io/badge/Tool-Power%20BI-yellow.svg)](https://powerbi.microsoft.com/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

---

## 📋 Table of Contents / جدول المحتويات
1. [Project Overview / نظرة عامة على المشروع](#-project-overview)
2. [Business Problem & Objectives / مشكلة وأهداف العمل](#-business-problem--objectives)
3. [Data Architecture & Modeling / هيكلة وتحويل البيانات](#-data-architecture--modeling)
4. [Dashboard Architecture & Sections / أقسام لوحة القيادة المعروضة](#-dashboard-architecture--sections)
   - [Cover / الواجهة الرئيسية](#1-cover--الواجهة-الرئيسية)
   - [Home (Overview) / نظرة عامة](#2-home-overview--نظرة-عامة)
   - [Sales & Clients Analytics / تحليل المبيعات والعملاء](#3-sales--clients-analytics--تحليل-المبيعات-والعملاء)
   - [Property Portfolio / محفظة العقارات والخصائص](#4-property-portfolio--محفظة-العقارات-والخصائص)
   - [Financial & Expenses / التفاصيل المالية والمصروفات](#5-financial--expenses--التفاصيل-المالية-والمصروفات)
5. [Key Technical Highlights / الميزات التقنية DAX & Power Query](#-key-technical-highlights)
6. [How to Explore / كيفية تصفح المشروع واستخدامه](#-how-to-explore)

---

## 🌟 1. Project Overview / نظرة عامة على المشروع
مشروع تحليلي متكامل لقطاع التطوير والاستثمار العقاري، مصمم خصيصاً لتحويل بيانات المبيعات، العقارات، والعمليات المالية المعقدة إلى **لوحات تحكم تفاعلية (Interactive Power BI Dashboards)** تدعم متخذي القرار في فهم اتجاهات السوق، تقييم أداء وسطاء المبيعات، ومراقبة الربحية بدقة عالية.

---

## 🎯 2. Business Problem & Objectives / مشكلة وأهداف العمل
* **التحدي:** تواجه شركات التطوير العقاري صعوبة في دمج بيانات المبيعات المتفرقة مع المصروفات التشغيلية وتقييم أداء المحفظة العقارية في مكان واحد.
* **الهدف:** بناء نظام BI ذكي يتيح لمديري الإدارة العليا:
  1. تتبع إجمالي المبيعات وصافي الأرباح لحظياً (Real-time tracking).
  2. تحديد العقارات الأكثر طلباً والمناطق الأكثر ربحية.
  3. مراقبة كفاءة فريق المبيعات والعملاء المستهدفين.

---

## ⚙️ 3. Data Architecture & Modeling / هيكلة وتحويل البيانات
* **Data Cleaning & ETL:** تم استخدام Power Query لتنظيف البيانات، توحيد صيغ التواريخ، التعامل مع القيم المفقودة، وهندسة الأعمدة المحسوبة (Calculated Columns).
* **Data Modeling:** بناء نموذج بيانات نجمي (Star Schema) يربط جدول الحقائق الرئيسي (Fact Table) بجداول الأبعاد (Dimension Tables) الخاصة بالعملاء، الوكلاء، والمواقع الجغرافية لضمان سرعة معالجة الاستعلامات (DAX Queries).

---

## 🖼️ 4. Dashboard Architecture & Sections / أقسام لوحة القيادة المعروضة

### 1. Cover / الواجهة الرئيسية
* **الوصف:** غلاف احترافي مصمم خصيصاً للمشروع يعكس هوية النظام الفاخرة في قطاع العقارات.
<img src="./Screenshots/Cover.jpg" width="100%">

### 2. Home (Overview) / نظرة عامة
* **المؤشرات الحيوية (KPIs):** إجمالي الإيرادات ($96.2M)، إجمالي المصروفات ($29.6M)، صافي الربح ($66.6M)، وإجمالي الوحدات المباعة (160 عقار).
<img src="./Screenshots/Home.jpg" width="100%">

### 3. Sales & Clients Analytics / تحليل المبيعات والعملاء
* **التحليلات:** دراسة سلوك العملاء، معدلات التحويل، وأداء وسطاء المبيعات لزيادة كفاءة الإغلاق.
<img src="./Screenshots/Sales.jpg" width="100%">

### 4. Property Portfolio / محفظة العقارات والخصائص
* **التحليلات:** توزيع العقارات حسب النوع والمساحة وعدد الغرف ومتوسط السعر ($586.5K).
<img src="./Screenshots/Property.jpg" width="100%">

### 5. Financial & Expenses / التفاصيل المالية والمصروفات
* **التحليلات:** تحليل تفصيلي لهيكل التكاليف، المصروفات التشغيلية، وهوامش الربح الصافي.
<img src="./Screenshots/Financial.jpg" width="100%">

---

## 🛠️ 5. Key Technical Highlights / الميزات التقنية DAX & Power Query
* **Advanced DAX Measures:** استخدام معادلات متقدمة لحساب النسب المئوية، التغير الشهري (MoM Growth)، والتجميعات الشرطية (CALCULATE, FILTER, DIVIDE).
* **Dynamic Formatting & UI/UX:** تطبيق Dark Theme مخصص لراحة العين يتماشى مع المعايير الحديثة لتصميم لوحات المعلومات البصرية.
* **Interactive Tooltips & Navigation:** استخدام أزرار التنقل السريع بين الصفحات وفلاتر زمنية ديناميكية.

---

## 🚀 6. How to Explore / كيفية تصفح المشروع واستخدامه
1. استعرض تفاصيل اللوحات أعلاه لأخذ نظرة شاملة على مخرجات المشروع.
2. تصفح صور اللوحات عالية الدقة الموجودة داخل مجلد `Screenshots/`.
3. المشروع مصمم كنموذج عرض احترافي (Portfolio Showcase) لإبراز مهارات هندسة البيانات وتحليل Business Intelligence.

---
© **Omar Mosaad Ahmed** - All Rights Reserved.