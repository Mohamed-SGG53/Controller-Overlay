# 🎮 Controller Overlay (PS5 / Xbox / General)

## English

### 📌 Overview

**Controller Overlay** is a Python-based application that displays a controller overlay on screen and shows real-time button presses.

Currently supported:

* ✅ General Controller (tested & working)
* ⚠ PS5 Controller (experimental)
* ⚠ Xbox Controller (experimental)

> The controller type that has been fully tested is **General Controller**.
> If you experience incorrect button mapping on **PS5** or **Xbox**, please report the issue.

---

### 🖥 System Requirements

* ✅ Windows 10 (64-bit)
* ✅ Windows 11 (64-bit)
* ❌ No internet connection required
* ❌ No additional software installation required

> The application runs locally and works completely offline.

---

### 🛠 Built With

* Python
* pygame
* Controller images inspired from: [https://gamepadviewer.com/](https://gamepadviewer.com/)

(PS5 black controller design and button press visuals were adapted to match the overlay style.)

---

### ⚙ How It Works

The application currently works with:

* 🎮 One controller only
* ❌ No GUI settings panel (simple configuration system for now)

All settings are managed through the file:

```
settings.ini
```

---

### 🎮 Select Active Controller

To change which controller is active:

```ini
active_controller = 1
```

* Change the number from **1 to 4**
* If it doesn’t work with `1`, try `2`, `3`, or `4`
* If none of them work, please report the issue

---

### 📍 Change Overlay Position

Modify this value inside `settings.ini`:

```ini
overlay_location = X
```

Where X is:

```
; overlay_location:
; 1 = bottom left
; 2 = bottom center
; 3 = bottom right
; 4 = center left
; 5 = center right
; 6 = top left
; 7 = top center
; 8 = top right
```

---

### 🚀 Current & Upcoming Support

* ✅ PS5 Black Controller
* 🔜 More controller designs coming soon
* 🔜 GUI Settings Panel (to make configuration easier without editing settings.ini manually)

---

### 📦 Version

```
Version: V1.0.0
Status: Stable
```

---

### 👨‍💻 Developer

Created by: **Mohamed Hisham**

---

---

# 🎮 Controller Overlay (PS5 / Xbox / General)

## العربية

### 📌 نظرة عامة

برنامج **Controller Overlay** هو تطبيق تم تطويره باستخدام Python لعرض شكل دراع الألعاب على الشاشة مع إظهار الضغطات التي يقوم بها المستخدم في الوقت الحقيقي.

الأنواع المدعومة حالياً:

* ✅ دراع General (تم اختباره ويعمل بشكل كامل)
* ⚠ دراع PS5 (تجريبي)
* ⚠ دراع Xbox (تجريبي)

> النوع الذي تم اختباره بالكامل هو **General Controller**
> في حالة وجود خطأ في إظهار الضغطات في **PS5 أو Xbox** يرجى الإبلاغ عنه.

---

### 🖥 متطلبات التشغيل

* ✅ ويندوز 10 نسخة 64 بت
* ✅ ويندوز 11 نسخة 64 بت
* ❌ لا يحتاج إلى اتصال بالإنترنت
* ❌ لا يحتاج إلى تثبيت أي برامج إضافية

> التطبيق يعمل محلياً بالكامل بدون أي متطلبات خارجية.

---

### 🛠 تم التطوير باستخدام

* Python
* pygame
* صور مستعارة من موقع: [https://gamepadviewer.com/](https://gamepadviewer.com/)

(تم الاستعانة بشكل دراع PS5 الأسود وتأثيرات الضغطات ليتوافق مع تصميم الـ Overlay)

---

### ⚙ طريقة التشغيل

حالياً التطبيق:

* يعمل على دراع واحد فقط
* لا يحتوي على واجهة إعدادات (حالياً يتم التعديل يدوياً)
* يتم التحكم في الإعدادات من خلال ملف:

```
settings.ini
```

---

### 🎮 تغيير رقم الدراع

قم بتعديل هذا السطر داخل الملف:

```ini
active_controller = 1
```

* يمكنك اختيار رقم من **1 إلى 4**
* إذا لم يعمل على رقم 1 جرب 2 ثم 3 ثم 4
* إذا لم يعمل بأي رقم يرجى إبلاغي لحل المشكلة

---

### 📍 تغيير مكان ظهور الـ Overlay

قم بتعديل القيمة:

```ini
overlay_location = X
```

القيم المتاحة:

```
; overlay_location:
; 1 = أسفل يسار
; 2 = أسفل المنتصف
; 3 = أسفل يمين
; 4 = منتصف يسار
; 5 = منتصف يمين
; 6 = أعلى يسار
; 7 = أعلى المنتصف
; 8 = أعلى يمين
```

---

### 🚀 الدعم الحالي والمستقبلي

* ✅ PS5 الأسود فقط
* 🔜 سيتم إضافة أشكال دراعات أخرى قريباً
* 🔜 سيتم إضافة واجهة إعدادات (GUI) لتسهيل التحكم بدون تعديل ملف settings.ini يدوياً

---

### 📦 الإصدار

```
الإصدار: V1.0.0  
الحالة: مستقر
```

---

### 👨‍💻 المطور

تم الإنشاء بواسطة: **محمد هشام**

---
