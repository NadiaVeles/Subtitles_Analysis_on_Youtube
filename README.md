# Subtitles_Analysis_on_Youtube
Это учебный проект "Анализ упоминаний брендов в российском YouTube"

Код работает в Colab и доступен по ссылкам:

Часть 1. https://colab.research.google.com/drive/160BASrgub2tGz6T802LUSqv_N_bfZu9T?usp=sharing

Часть 2. https://colab.research.google.com/drive/1vow_2Tfp29UZRYDM9kxqcCZkyc7IW5Qg?usp=sharing

Часть 3. https://colab.research.google.com/drive/1_Y2hT5NHGjOVadpsnfGXgkg4iJHjsEHI?usp=sharing

ЦЕЛИ ПРОЕКТА

Анализ присутствия и упоминания брендов в русскоязычном YouTube-контенте. Выявление паттернов рекламных интеграций. Создание автоматизированной системы мониторинга упоминаний брендов. Разработка инструментов анализа контента на русском языке.

ЗАДАЧИ ПРОЕКТА

•	Получение видео с популярных российских YouTube-каналов
•	Извлечение субтитров и транскриптов
•	Сохранение метаданных (название, дата публикации, канал)
•	Обработка русскоязычных текстов
•	Распознавание брендов с учетом различных вариаций написания
•	Определение контекста упоминаний
•	Выявление рекламных паттернов
•	Создание наглядных графиков и диаграмм
•	Визуализация трендов и паттернов

ИНСТРУМЕНТЫ

Для сбора данных:
•	youtube_transcript_api
•	googleapiclient.discovery
•	pandas

Для обнаружения брендов:
•	nltk (word_tokenize + stopwords)
•	pymorphy3
•	matplotlib
•	pandas

Для анализа и визуализации:
•	pandas
•	matplotlib
•	wordcloud

