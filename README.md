### Выполнил Ахатов Тимур Ильдарович, М8О-406Б-21

# Лабораторная работа 7
## Результат
| Модель                                     | IoU |
| ------------------------------------------ | ------ |
| UNET + Resnet Базовый Baseline             | 0.4414 |
| UNET + Resnet Улучшенный Baseline          | 0.4557 |
| UNET + MiT Базовый Baseline                | 0.4754 |
| UNET + MiT Улучшенный Baseline             | 0.4953 |
| Собственная реализация UNET                    | 0.0284 |
| Собственная реализация UNET Улучшенный Baseline| 0.0363 |
## Вывод
В результате проведённой работы произошло сравнение двух подходов к решению задачи семантической сегментации. Был сравнён трансформер и CNN архитектуры, несмотря на больший размер CNN показал худшие результаты. Лучше всех себя показала старшая MiT модель(mit_b1  ). Собственная реализация не показала никаких результатов.


# Лабораторная работа 8
## Результат
| Модель                                     | mAP | mAP50 |
| ------------------------------------------ | ------ | -------- |
| YOLOv8n Базовый Baseline                      | 0.8668 | 0.9897  |
| YOLOv8m Улучшенный Baseline                   | 0.9128 | 0.9950  |
| Собственная реализация                      | 0.0 | 0.0   |



## Вывод
Результат работы был предсказуем, модели YOLO из ultralystics, показали лучшие результаты. Также стоит подчеркнуть, что YOLOv8 nano показала отличные результаты, по сравнению со своим средним братом YOLOv8 medium. Разницу между ними в этой задачи можно считать незначительной. И это можно объяснить тем, что задача неслишком сложна для младшей версии, и старшая версия не может на этой задачи полностью раскрыть свои преимущества. 

