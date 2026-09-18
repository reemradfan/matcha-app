# استخدام سيرفر خفيف ونظيف لتشغيل صفحات الويب
FROM nginx:alpine

# نسخ ملفات الموقع إلى مجلد العرض الخاص بالسيرفر
COPY . /usr/share/nginx/html

# فتح المنفذ الأساسي
EXPOSE 80

# تشغيل السيرفر
CMD ["nginx", "-g", "daemon off;"]
