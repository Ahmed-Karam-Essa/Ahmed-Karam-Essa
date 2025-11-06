# افتح فولدر المشروع أو أنشئ واحد جديد
mkdir Ahmed-Karam-Essa
cd Ahmed-Karam-Essa

# ابدأ مستودع محلي
git init

# أنشئ ملف README.md وادخل عليه المحتوى (مثلاً افتح محرر نص)
# ثم احفظ الملف

# اضف كل الملفات ثم اعمل commit
git add README.md
git commit -m "Add README"

# اربط الريبو بالمستودع على GitHub (استبدل المسار لو تستخدم SSH)
git remote add origin https://github.com/Ahmed-Karam-Essa/Ahmed-Karam-Essa.git

# ادفع التغييرات للفرع الرئيسي
git branch -M main
git push -u origin main
