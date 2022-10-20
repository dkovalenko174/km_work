- title: Заявка №001
- employee: Вагина

---

## Гант
```mermaid
gantt
dateFormat YYYY-MM-DD
title Доставка по заявке 1 и 2
excludes weekdays 2022-10-03

section Договор
Заключение договора :done, des1, 2022-10-03, 2022-10-07

section Спецификация
Согласование :done, des2, after des1, 3d
Подписание :done, des3, after des2, 1d

section Оплата
Получение счета :done, des4, after des3, 1d
Оплата счета :done, des5, after des3, 1d

section Логистика
Получение ТЭО :done, des6, after des3, 1d
```

## TODO