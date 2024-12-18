# Project QR-code generator
 Курская Полина Сергеевна (ИСУ: 475143),
 Хабибулина Софья Аркадьевна (ИСУ: 467896)

## Распределение обязанностей:
- Хабибулина Софья - писала код в main.py
- Курская Полина - писала модули (NewYear, Halloween, Womenday) 
---
## Описание проекта:
- Создание и кастомизация QR-кода на определённую тематику (праздник) с возможностью изменения цвета QR-кода под запрос пользователя. Это возможность оригинально поздравить кого-то с тем или иным праздником, так как за каждым QR-кодом закреплена открытка с поздравлением!
---
## Пример реализации №1 (стандартный QR-code):
$ python main.py

Какой праздник вам больше нравится/необходим для создания QR-кода (Новый год, Хэллоуин, 8 марта)? 
> Новый год
> 
Вы выбрали: Новый год

Вы хотите создать тематический QR-код для вашего любимого праздника? (Если хотите стандартный, напишите "нет") (да/нет):
> нет
> 
Ваш QR-код сохранен в basic_qrcode.png

- (Если вы сделали неправильный ввод, то программа попросит реализовать ввод снова либо завершится (необходимо придерживаться шаблона!!!)).
---
## Пример реализации №2 (тематический QR-code, например, на тему Новый год):
$ python main.py

Какой праздник вам больше нравится/необходим для создания QR-кода (Новый год, Хэллоуин, 8 марта)? 
> Новый год
> 
Вы выбрали: Новый год

Вы хотите создать тематический QR-код для вашего любимого праздника? (Если хотите стандартный, напишите "нет") (да/нет): 
> да
> 
Выберите тематику ещё раз (Новый год, Хэллоуин, 8 марта): 
> Новый год
> 
Выберите цвет QR-кода (синий, голубой, красный, чёрный): 
> красный
> 
QR-код с рамкой сохранен как your_qrcode.png
![image](https://github.com/user-attachments/assets/fc8d3517-6bd6-4943-a9b3-d8de7e0cb3f3)
- (Если вы сделали неправильный ввод, то программа попросит реализовать ввод снова либо завершится (необходимо придерживаться шаблона!!!)).
---
## !!!Примечание: 
Если Вы выбрали тусклый цвет или двойной (розовый, светло-зелёный, чëрно-жëлтый, и т.д.), то, к сожалению, телефон не всегда сможет отсканировать QR-код. Поэтому, если Вы хотите отсканировать и перейти по ссылке, то выбирайте более тёмные цвета. Если просто хотите поэкспериментировать, то выбирайте любые цвета, дизайн получится прикольный!
