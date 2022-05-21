# *Хакатон 2022*

*Команда:*
Шишканов Георгий,
Протасов Егор,
Катюшин Илья,
Смирнов Александр,
Карпенко Глеб

# *Кейс:*
Обнаружение атак на завод по очистке воды
Ссылка на описание датасета и исходные данные: https://docs.google.com/document/u/0/d/1w6TaAbxSx8M22MZvN3iIPNl-6V5OIt3FcdFUajPyGnE/mobilebasic

# *Результаты исследования:*
Данные были собраны в один датасет. Далее обработаны для удобства работы с моделями, очищены от некорректных текстовых значений.
Было проведено исследование с помощью нескольких моделей машинного обучения: модели классификации и кластеризации были обучены для обнаружения атак на системы очистки воды и готовы к использованию на реальных данных. Модель TadGAN была обучена на обрезанных данных, поэтому она нуждается в полноценном обучении.

# *Структура:*
Собранные данные: https://drive.google.com/file/d/120fgForM_FPs6VLorTEehhbjagJfJBRv/view?usp=sharing
Model_Learning - обучение моделей и исследование
Data_Downloading/Download_Data - скрипт сбора данных в один датасет
