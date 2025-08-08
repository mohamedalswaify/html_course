
# 🚀 رفع مشروع إلى GitHub باستخدام VS Code

## ✅ المتطلبات قبل البدء:
1. حساب GitHub ([التسجيل هنا](https://github.com/))
2. تثبيت Git: [git-scm.com/downloads](https://git-scm.com/downloads)
3. VS Code يحتوي على Git (غالبًا يكون مدمج تلقائيًا)

---

## 🧭 الخطوات الكاملة:

### 🔹 الخطوة 1: فتح المشروع في VS Code
- افتح VS Code
- من القائمة: `File > Open Folder` واختر مجلد المشروع

---

### 🔹 الخطوة 2: فتح التيرمنال Terminal

اضغط:
```bash
Ctrl + `
```

---

### 🔹 الخطوة 3: إعداد بيانات Git لأول مرة

```bash
git config --global user.email "your_email@example.com"
git config --global user.name "Your Name"
```

✏️ غيّر `your_email@example.com` و `Your Name` إلى بياناتك.

---

### 🔹 الخطوة 4: تهيئة Git في المشروع

```bash
git init
```

---

### 🔹 الخطوة 5: إضافة كل الملفات إلى Git

```bash
git add .
```

---

### 🔹 الخطوة 6: عمل أول Commit

```bash
git commit -m "First commit"
```

---

### 🔹 الخطوة 7: إنشاء مستودع جديد على GitHub
- اذهب إلى [GitHub](https://github.com/)
- ➕ ثم `New repository`
- اكتب اسم المشروع (مثل: `my-first-project`)
- ❌ لا تضف README
- اضغط **Create repository**

---

### 🔹 الخطوة 8: ربط المشروع بـ GitHub

بعد نسخ رابط GitHub، نفّذ:

```bash
git remote add origin https://github.com/username/my-first-project.git
git branch -M main
git push -u origin main
```

---

## 🎉 تهانينا! تم رفع المشروع على GitHub

---

## 🔁 لرفع تحديثات مستقبلية:

```bash
git add .
git commit -m "وصف مختصر للتعديلات"
git push
```

مثال:
```bash
git add .
git commit -m "Fixed login bug"
git push
```
