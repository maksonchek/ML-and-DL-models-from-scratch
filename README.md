Данный проект создан с целю понять внутреннее устройство классических алгоритмов машинного обучения и их оптимизаций, метрик, методов предобрабокти данных. Эта цель достигается путём теоретического описания и самостоятельной имплементации всего вышеперечисленного, используя только numpy.

На данный момент проект содержит следующие разделы: (которые будут пополняться каждую неделю)
## Datasets:
### 1) Классификация - классификация ценовых категорий смартфонов
### 2) Регрессия
В этм разделе подготавливаются датасеты для тестирования собственных имплементаций. Также здесь разобраны все аспекты предобработки данных (Работа с категориальными признаками, feature-engineering, стандартизация, нормализация, работа с выбросам и т.д)

## KNN:
Содержит математическое описание алгоритма для задач классфикации и регрессии. Описаны модификации KNN (Взвешивание соседей с учётом индекса ранжированных по расстоянию объектов, метод Парзеновского окна, метрики расстояния, функции ядра)

Всё, что описано в теории также реализовано в коде. Проведено тестирование и сравнение с реализацие в sklearn

### Источники
1) [Курс лекций и семинаров МФТИ](https://www.youtube.com/playlist?list=PLk4h7dmY2eYFmowaPqjFDzSokiiLq5TkT)
2) [girafe-ai](https://github.com/girafe-ai/ml-course)
3) [Хэндбук по ML от Яндекса](https://education.yandex.ru/handbook/ml)
4) Множество сайтов, ютуб-каналов, которые будут упомянуты позже