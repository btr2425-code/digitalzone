# DigitalZone — دليل الرفع والإعداد

## هيكل المشروع
```
digitalzone/
├── index.html          ← الموقع الرئيسي
├── netlify.toml        ← إعدادات Netlify
├── admin/
│   ├── index.html      ← لوحة التحكم (Decap CMS)
│   └── config.yml      ← إعدادات لوحة التحكم
└── _data/
    ├── products.json   ← بيانات المنتجات
    ├── categories.json ← بيانات الفئات
    └── settings.json   ← إعدادات الموقع
```

## خطوات الرفع على Netlify

### 1. ارفع المشروع على GitHub
1. روح github.com وسجّل أو ادخل
2. اضغط New repository → اسم المشروع → Create
3. ارفع كل الملفات (upload files)

### 2. اربطه بـ Netlify
1. روح netlify.com → Add new site → Import from Git
2. اختر GitHub والـ repo اللي سويته
3. Build command: اتركه فاضي
4. Publish directory: . (نقطة)
5. اضغط Deploy

### 3. فعّل Netlify Identity
1. في لوحة Netlify → Site settings → Identity → Enable Identity
2. تحت Registration → Invite only
3. تحت Git Gateway → Enable Git Gateway
4. ادعو نفسك: Identity → Invite users → أدخل إيميلك

### 4. ادخل لوحة التحكم
- الرابط: yoursite.netlify.app/admin
- سجّل بالإيميل اللي دعوته

## تعديل المحتوى من لوحة التحكم
- **المنتجات**: أضف/حذف/عدّل أي منتج بسهولة
- **الفئات**: أضف فئات جديدة وتظهر تلقائياً في الفلاتر
- **إعدادات الموقع**: عدّل العنوان والألوان والإحصائيات
