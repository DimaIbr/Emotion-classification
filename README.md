# Emotion-classification
Сравнение моделей из SkLearn и CatBoost в задаче многоклассовой определения эмоций

Эмоции 01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised

Ссылка на датасет:
https://zenodo.org/records/1188976

Итоги:
Лучше всего подошёл метод опорных векторов из предствленных в sklearn

Train set Accuracy: 0.9992283950617284

Test set Accuracy: 0.7916666666666666

kernel='rbf', gamma='auto', C=10
