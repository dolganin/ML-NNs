# Введение в NLP

В данном задании вы познакомитесь с одной из базовых задач NLP - text classification.

#### Задание:
1. Взять модель https://huggingface.co/DeepPavlov/rubert-base-cased-conversational (если хотите, то можете использовать что-то другое)
2. Взять любой русскоязычный датасет для классификации текста (например, https://huggingface.co/datasets/blinoff/kinopoisk)
3. Обучить модель для классификации текста, учитывая специфику вашего датасета (например, для примера выше необходимо обучить модель отличать положительные рецензии на фильм от отрицательных)
4. Добавить возможность ввода пользовательского текста для оценки его моделью. 

Для обучения использовать библиотеку transformers.
Во время сдачи задания вам необходимо будет рассказать про архитектуру модели, показать полученную метрику, ответить на общие вопросы по NLP.