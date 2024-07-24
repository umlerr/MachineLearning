# MachineLearning

## ЛАБОРАТОРНАЯ РАБОТА №1

### Подготовка и нормализация данных

![image](https://github.com/user-attachments/assets/2d47a3b0-d55f-4bd4-8209-890d48d0f74b)

![image](https://github.com/user-attachments/assets/23e108d9-bb8a-4bc1-b2ea-7299d6133f88)

![image](https://github.com/user-attachments/assets/a3c83898-ab48-43f6-95ea-9cd25e520363)

![image](https://github.com/user-attachments/assets/6e85fafe-707f-4421-a0da-fa3dc9fb447f)

## ЛАБОРАТОРНАЯ РАБОТА №2

### Классификация

Цель работы: целью данной работы является изучение и практическое применение методов классификации в контексте машинного обучения. Основная цель заключается в обучении моделей и подборе параметров, оценки моделей.

Задачи работы: в рамках данной работы необходимо выполнить следующие задачи - изучить основные принципы и методы классификации, подобрать параметры и обучить модели, оценить модели.

## ЛАБОРАТОРНАЯ РАБОТА №3

### Классификация

Цель работы: получение и закрепление навыков предобработки данных и применение методов машинного обучения для решения задач кластеризации.

Задачи:
1.	Обучение моделей и подбор параметров
2.	Оценка обученных моделей

KMeans. Метод K-средних.

![image](https://github.com/user-attachments/assets/3874480a-be57-4767-a2ff-ed3de23eddd7)

![image](https://github.com/user-attachments/assets/b4cfe802-3f16-41d4-a607-3deeb4e91b1c)

![image](https://github.com/user-attachments/assets/8ceb4b67-be7f-4731-a153-8ecd80e3b046)

![image](https://github.com/user-attachments/assets/05bb7d9b-beef-42b6-97ac-b6a8e568cd9a)

![image](https://github.com/user-attachments/assets/4127297c-12e9-4d23-b138-fcc060645449)

Иерархическая кластеризация

![image](https://github.com/user-attachments/assets/34e777b2-d81c-46b4-8af3-3a9740b913c1)

![image](https://github.com/user-attachments/assets/394ffeca-234e-40ec-a8b6-29c8f9443806)

DBSCAN

![image](https://github.com/user-attachments/assets/084c0daa-6d0c-4faf-b4b4-adff6178e7c6)

## ЛАБОРАТОРНАЯ РАБОТА №4

### Регрессия

Цель работы 

Целью данной работы служит получение и закрепление навыков предобработки данных и применения методов машинного обучения для решения задач регрессии на датасете, полученном из исследования производительности ноутбуке.

Задачи

В рамках данной работы необходимо выполнить следующие задачи:
1.	Подготовить датасет для обучения моделей: преобразовать данные, отобразить значимые признаки, нормализовать данные.
2.	Обучить модели и подобрать параметры тремя способами: линейная регрессия, LASSO, 	ридж-регрессия.
3.	Визуализировать предсказанные значения.

Линейная регрессия

![image](https://github.com/user-attachments/assets/cc16df84-07d6-466d-9ac5-caf740f813f2)

- Точность на тестовом наборе: 87,43% — это точность модели на отложенном наборе данных (тестовом наборе). Значение в 87.43% говорит о том, что модель правильно предсказывает зависимую переменную для 87.44% наблюдений в тестовом наборе.
- Точность на обучающем наборе: 87,44% — это точность модели на обучающем наборе данных. Значение в 87.44% означает, что модель правильно предсказывает зависимую переменную для 87.44% наблюдений в обучающем наборе.
- Значение Mean Squared Error (MSE) указывает на среднеквадратичную ошибку модели в предсказании зависимой переменной. Чем ниже значение MSE, тем ближе предсказанные значения к реальным значениям. В данном случае, значение MSE равно 71.20489778431056, что означает, что средняя квадратичная ошибка предсказания составляет примерно 71.2.
- Коэффициент детерминации (R^2) - это мера, которая оценивает, насколько хорошо модель соответствует данным. Значение в 0.8743634121194086 указывает на то, что примерно 87.44% вариации зависимой переменной может быть объяснено моделью. Чем ближе коэффициент детерминации к единице, тем лучше соответствие модели данным.
- Средняя абсолютная ошибка (MAE): 0.874 — Это среднее абсолютное значение ошибки между предсказанными и фактическими значениями. Меньшее значение MAE также указывает на более точные предсказания модели.
- Сходство параметров – Точность на тестовом наборе, Точность на обучающем наборе и Коэффициент детерминации указывает на то, что модель хорошо обобщает данные и демонстрирует неплохую предсказательную способность. 
- Модель имеет довольно высокую точность как на обучающем, так и на тестовом наборе данных.

LASSO

![image](https://github.com/user-attachments/assets/6d7ad789-6c31-4e0f-bb0c-1e92da1078d6)

- При подборе параметров методом GridSearch коэффициент альфа (α), играющий ключевую роль в контроле степени регуляризации модели и использующийся для управления сложностью модели и предотвращения переобучения, был выбран 0.001. При таком подборе данного параметра точность модели достигается максимальной и схожа с линейной регрессий из первого пункта. Коэффициент альфа (α) в методе Lasso определяет силу регуляризации и влияет на количество признаков, которые будут отобраны моделью. Выбор оптимального значения альфа требует баланса между сложностью модели и ее предсказательной способностьюКогда  альфа (α) установлено в ноль, Lasso регрессия стремится минимизировать только сумму квадратов ошибок модели, без применения штрафа на величину коэффициентов. В результате, Lasso регрессия в этом случае выбирает только наиболее важные и информативные признаки, назначая им ненулевые коэффициенты, а остальные признаки получают нулевые коэффициенты.
- Если установить значение альфа равным нулю в методе Lasso регрессии, мы получим модель, которая будет выбирать все доступные признаки без ограничений. Это может быть наилучший выбор, когда мы хотим сохранить все признаки и обеспечить высокую предсказательную способность модели. 
- Модель имеет довольно высокую точность как на обучающем, так и на тестовом наборе данных.

Ridge регрессия

![image](https://github.com/user-attachments/assets/1868344d-e6cb-4702-bfc9-05575fe22f7b)

- Ridge регрессия - это метод линейной регрессии, который включает регуляризацию с помощью L2 нормы коэффициентов. Регуляризация служит для управления сложностью модели и предотвращения переобучения.
- Точность модели на тестовом наборе данных: 87.43681536963264% - это показатель, который указывает на качество предсказаний модели на новых данных, которые она не видела во время обучения. 
- Точность модели на обучающем наборе данных: 87.44841767959038% - это показатель, который указывает на точность модели на данных, которые она использовала для обучения. Высокая точность на обучающем наборе данных может означать, что модель хорошо соответствует этим данным.
- В случае Ridge регрессии, альфа (α) - это гиперпараметр, который управляет силой регуляризации. Значение альфа (α) = 10 указывает на средний уровень регуляризации.
- Среднеквадратичная ошибка (MSE): 71.20221048194536 - это средняя квадратичная ошибка между предсказанными значениями модели и фактическими значениями. Чем ниже значение MSE, тем лучше модель соответствует данным.
- Коэффициент детерминации (R^2): 0.8743681536963264 - это мера, которая показывает, как хорошо модель объясняет вариацию в данных. Значение R^2 близкое к 1 означает, что модель хорошо объясняет данные.
- Средняя абсолютная ошибка (MAE): 6.412155266030508 - это среднее абсолютное отклонение между предсказанными значениями модели и фактическими значениями. Чем ниже значение MAE, тем лучше модель соответствует данным.
- Сходство параметров – Точность на тестовом наборе, Точность на обучающем наборе и Коэффициент детерминации указывает на то, что модель хорошо обобщает данные и демонстрирует неплохую предсказательную способность.
