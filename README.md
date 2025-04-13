# writer-classification

# Классификация авторов текстов

Проект для конкурса WriterExtnd, использующий глубокое обучение для определения авторства текстов.

## Ресурсы проекта

- [Google Colab ноутбук с полным кодом](https://colab.research.google.com/drive/1kubST_900me4JukfGHV5ej2Q_xEN6UrQ?usp=sharing)
- [Официальная страница конкурса WriterExtnd](https://www.kaggle.com/competitions/writerextnd/overview)

## Описание проблемы и постановка целей
Проект направлен на решение задачи классификации авторов литературных произведений на основе их текстов. Используется датасет конкурса WriterExtnd, содержащий тексты 6 различных писателей. Основная цель - построить модель, способную точно определять авторство неизвестных текстовых отрывков.

## Подход и методы
Для решения задачи применяются методы глубокого обучения:
- Обработка текстовых данных с использованием токенизации
- Построение нейронной сети с архитектурой, адаптированной для текстовой классификации
- Обучение модели с подбором оптимальных гиперпараметров

## Результаты и выводы
На основе проведенного обучения можно сделать следующие выводы:
1. Точность модели на валидационной выборке, указывает на недостаточную эффективность текущего подхода
2. Анализ кривых обучения показывает, что модель не способна выйти за пределы базового уровня точности
3. Основные проблемы могут быть связаны с:
   - Недостаточным объемом обучающих данных
   - Неоптимальной архитектурой модели
   - Особенностями предобработки текстов

### Рекомендации по улучшению:
1. Увеличить объем обучающих данных с помощью аугментации текстов
2. Использовать предобученные языковые модели (BERT, GPT)
3. Экспериментировать с другими архитектурами (LSTM, Transformers)
4. Применить более сложные методы предобработки текста
5. Использовать кросс-валидацию для более надежной оценки

### Требования:
- Python 3.8+
- TensorFlow 2.0+
- Keras
- NLTK
- Pandas
- NumPy
- 


## Как использовать

1. Откройте ноутбук в Google Colab:
   - Нажмите на ссылку выше
   - Нажмите "Открыть в Google Colab" (требуется аккаунт Google)
   - Для запуска выберите "Runtime" → "Run all"

2. Альтернативно, вы можете скачать ноутбук:
   ```bash
   wget https://colab.research.google.com/drive/1kubST_900me4JukfGHV5ej2Q_xEN6UrQ?usp=sharing -O writer_classification.ipynb

## Установка

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/Volkova74-git/writer-classification.git

## Для локального запуска (если скачаете ноутбук):
pip install tensorflow keras numpy pandas matplotlib


   
   
