# Классификация твитов с упоминаниями катастроф

[Kaggle: Natural Language Processing with Disaster Tweets](https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fcompetitions%2Fnlp-getting-started)

**Цель:**

Построить модель, определяющую, упоминается ли в твите настоящая катастрофа.

**План работ:**

1.  Загрузка и анализ данных
2.  Подготовка данных (очистка твиттов, лемматизация)
3.  Обучение LogisticRegression на TF-IDF фичах
4.  Fine-tuned BERT

**Результат:**
TF-IDF + LogReg: Score: 0.78179
BERT: Score: 0.83941

