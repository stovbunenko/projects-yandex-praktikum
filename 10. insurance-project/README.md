**Защита персональных данных клиентов**

- Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
- Целевой признак: количество страховых выплат клиенту за последние 5 лет.

**Цель:**

- Нужно защитить данные клиентов страховой компании «Хоть потоп». 
- Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию и обосновать корректность его работы. 
- Защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. 
- Подбирать наилучшую модель не требуется.

**Выводы проекта:**

- Все данные в датасете заполнены (пропусков нет).
- Типы данных изменений не требуют.
- Значительных выбросов и аномальных значений не выявлено.
- Выявлены и удалены дубликаты.
- Предобработка данным не нужна
- Метрики R2 обеих моделей одиннаковые, а значит умножение исходных данных на случайную обратимую матрицу может быть применено для их шифрования

**Стек:**

import pandas, IPython.display, matplotlib.pyplot, numpy, seaborn, sklearn

**Статус проекта:**

Завершен.
