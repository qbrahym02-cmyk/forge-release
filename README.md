# Forge Desktop — official download page

<div dir="rtl">

## صفحة التحميل الرسمية لبرنامج Forge Desktop

برنامج بناء تطبيقات الويب بالذكاء الاصطناعي — نسخة سطح المكتب لـ Windows.

### التحميل المباشر

| الملف | الوصف | الحجم التقريبي |
|-------|-------|-----------------|
| `Forge-Setup-1.0.0.exe` | **المثبّت الرسمي** — انقر نقراً مزدوجاً وثبّت | ~166 MB |
| `Forge-1.0.0-win.zip` | نسخة محمولة — فك الضغط وشغّل `Forge.exe` مباشرة | ~226 MB |
| `forge-desktop-complete.zip` | الحزمة الكاملة: الكود المصدري + المثبّت + بصمات SHA-256 | ~177 MB |

### خطوات التثبيت (Windows)

1. حمّل ملف `Forge-Setup-1.0.0.exe`
2. انقر نقراً مزدوجاً على الملف → اتبع خطوات المثبّت
3. شغّل البرنامج من قائمة ابدأ → **Forge**
4. عند أول تشغيل يُزرع البرنامج قاعدة بياناته المحلية تلقائياً — لا حاجة لأي إعداد

### التحقق من سلامة الملف

بعد التحميل تحقق من بصمة SHA-256:

```powershell
certutil -hashfile Forge-Setup-1.0.0.exe SHA256
```

قارنها بالبصمة المنشورة في صفحة [الإصدار v1.0.0](https://github.com/qbrahym02-cmyk/forge-release/releases/tag/v1.0.0).

### ملاحظات

- يعمل البرنامج بدون إنترنت بعد التثبيت (قاعدة بيانات محلية SQLite)
- كل عمليات التراجع والاستعادة **لا تحذف أي ملف** — مع نسخ احتياطية تلقائية قبل كل استعادة
- كود المصدر الكامل متوفر داخل `forge-desktop-complete.zip`

</div>

---

## Downloads

| File | Description |
|------|-------------|
| `Forge-Setup-1.0.0.exe` | **Official installer** — double-click to install |
| `Forge-1.0.0-win.zip` | Portable build — unzip and run `Forge.exe` |
| `forge-desktop-complete.zip` | Complete bundle: source code + installer + SHA-256 checksums |

Verify integrity after download:

```bash
sha256sum Forge-Setup-1.0.0.exe
```
