# face_expression_recognize_CNN

## modules:

[![Generic badge](https://img.shields.io/badge/python-3.9-yellow.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/numpy-1.26.4-green.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/pandas-2.1.4-red.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/tensorflow-2.9.0-orange.svg)](https://shields.io/)

در این پروژه ابتدا از open-cv برای خواندن عکس ها استفاده شده
سپس از تکنیک augmentation برای دیتا استفاده کردم و از سه لایه فیتر cnn و سپس دو لایه مخفی و یک لایه از sigmoid avtivation function استفاده کردم.
با توجه به اینکه گرافیک سیستم ضعیف بود از batching و piplines نتونستم استفاده کنم. برای train مدل از CPU استفاده کردم.

model score : 0.4850
