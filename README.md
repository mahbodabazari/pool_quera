# حل مسئله استخرمون نشه - Quera

**آدرس سوال:** [quera.org/problemset/251285](https://quera.org/problemset/251285)

---



در این پروژه با استفاده از یادگیری عمیق و فریمورک PyTorch، مسئله شناسایی پوشه‌هایی که شامل تصاویر استخر هستند را حل کردم.  
ابتدا داده‌ها را تمیز کرده و آماده‌سازی نمودم. سپس با استخراج مسیر تصاویر بر اساس فایل JSON داده‌های آموزشی، از یک مدل پیش‌آموزش‌دیده برای استخراج ویژگی‌ها استفاده کردم.  
در نهایت یک مدل باینری آموزش دادم که هر پوشه را ارزیابی می‌کند و در صورتی که حتی یک تصویر استخر در پوشه وجود داشته باشد، آن پوشه را به عنوان «استخر» تشخیص می‌دهد.

---



**Solving the "Our Pool Should Not Be" challenge on Quera**  
**Problem link:** [quera.org/problemset/251285](https://quera.org/problemset/251285)

In this project, I addressed the task of identifying folders containing pool images using deep learning and the PyTorch framework.  
First, I cleaned and preprocessed the dataset. Then, based on the training JSON file, I extracted image paths and utilized a pre-trained model for feature extraction.  
Finally, I trained a binary classification model that examines each folder and classifies it as "pool" if it contains even a single pool image.
