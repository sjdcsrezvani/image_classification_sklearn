# iranian celebrity image classification

## requirements:

[![Generic badge](https://img.shields.io/badge/python-3.9-yellow.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/numpy-1.26.4-yellow.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/pywavelet-1.6.0-blue.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/open_cv-4.10.0-red.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/scikit_learn-1.4.2-green.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/flask-3.0.3-red.svg)](https://shields.io/)

## description:

در این پروژه از عکس های 4 بازیگر ایرانی استفاده کردم و با استفاده از کتابخانه open-cv و haarcascade باکس صورت و چشم های عکس ها را شناسایی کردم و صورت های مورد نظر crop شدند.

سپس از pywavelet transformation استفاده کردم تا عکس ها اطلاعات بهتری در اختیار مدل قرار بدهند.

سپس اطلاعات عکس ها را تبدیل به array کردم. و با استفاده از standard-scaler داده ها را scale کردم تا دقت مدل بالاتر برود.

و از gridsearch cv برای hyper-parameter-tuning استفاده کردم. و از مدل SVC استفاده کردم، دقت مدل 0.875 

و برای ساخت صفحه وب از کتابخانه flask برا بک اند .

برای استفاده از مدل ابتدا فایل [server.py](./server/server.py) را اجرا کنید، سپس فایل [app.html](./UI/app.html) را اجرا کنید.

### so in this project i used these techniques:
1. open-cv
2. haarcascade
3. pywavelet-transfomation
4. gridsearch-cv
5. sklearn
6. hyper-parameter tuning
7. SVC
8. flask
9. javascript

### webpage images:
![Screenshot 2024-08-03 134724](https://github.com/user-attachments/assets/fc644c3d-bca9-4636-b9d4-d88cf7c68313)

here it will give us the score for each category:

![Screenshot 2024-08-03 134844](https://github.com/user-attachments/assets/2f521419-509e-4d8c-ae74-7141c6050e9a)
