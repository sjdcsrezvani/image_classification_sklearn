# iranian celebrity image classification

در این پروژه از عکس های 4 بازیگر ایرانی استفاده کردم و با استفاده از کتابخانه open-cv و haarcascade باکس صورت و چشم های عکس ها را شناسایی کردم و صورت های مورد نظر crop شدند.

سپس از pywavelet transformation استفاده کردم تا عکس ها اطلاعات بهتری در اختیار مدل قرار بدهند.

سپس اطلاعات عکس ها را تبدیل به array کردم. و با استفاده از standard-scaler داده ها را scale کردم تا دقت مدل بالاتر برود.

و از gridsearch cv برای hyper-parameter-tuning استفاده کردم. و از مدل SVC استفاده کردم، دقت مدل 0.875 

و برای ساخت صفحه وب از کتابخانه flask برا بک اند ، و js برای فرانت استفاده کردم.

برای استفاده از مدل ابتدا فایل server.py را اجرا کنید، سپس فایل app.html را اجرا کنید.

so in this project i used these techniques:
1. open-cv
2. haarcascade
3. pywavelet-transfomation
4. gridsearch-cv

webpage images:
![Screenshot 2024-08-03 134724](https://github.com/user-attachments/assets/fc644c3d-bca9-4636-b9d4-d88cf7c68313)

here it will give us the score for each category:

![Screenshot 2024-08-03 134844](https://github.com/user-attachments/assets/2f521419-509e-4d8c-ae74-7141c6050e9a)
