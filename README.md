# Идея продукта
Использование нейросетей для оценки отклика зрителей на целевое видео. Это позволит выявлять смешные и скучные момненты видео, а так же анализировать реакцию различных социально-демографических групп.

# Что делаем?
1. Привязываем эмоции зрителей к кадрам видео;
2. Обучаем модель угадывать эмоции зрителя;
3. Cкорим видео по эмоциональному отклику. 

# Где применяем?
Монтаж видео: Формируем увеличивающие просмотры трейлеры и тизеры к видео, содержащие наиболе эмоциональный контент для выбранного сегмента целевой аудитории.

Пост-анализ эффективности: Формируем аналитику по эмоциональному отклику зрителей на видеоконтект. Инсайты могут быть учтены при написании сценариев.

# Мотивация
Необходимо замотивировать зрителя, чтобы он дал разрешение на анализ своих данных:

1. Контрольная группа - специально нанятые люди для анализа новых роликов.
2. Обычные зрители - промо-коды, бесплатный контент, другие плюшки.

# Видео-презентация
https://www.youtube.com/watch?v=Ed0NJqM8M8A

-----------------------------------------------

# Used Software
1. Python 3.5;
2. CNN to detect age, gender on pictures;
2. CNN to detect emotions + opencv to crop faces from stream / video file;
3. OpenCV, Keras (tensorflow).

-----------------------------------------------

# Launch

1. Download model weights from https://github.com/yu4u/age-gender-estimation/releases/download/v0.5/weights.18-4.06.hdf5 and put it in 'models/' folder.
2. Run 'emotions_recorder.ipynb' to analyse stream from web-cam or video-file. Save result with "time,reaction,reaction_tense,age,gender" columns in .csv format.
3. Run 'emotions_analyser.ipynb' to draw charts of your user's reaction by second. 

