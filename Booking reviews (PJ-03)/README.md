# Booking Reviews

## Описание проекта
Прогнозирование рейтинга отеля на Booking.  
Цель — предсказать оценку отеля (`reviewer_score`) на основе данных об отеле, пользователе и метаданных отзыва.

---

## Используемые модели
- **RandomForestRegressor** — baseline модель
- **CatBoostRegressor** — финальная модель

CatBoost выбран из-за хорошей работы с табличными данными и категориальными признаками.

---

## Стек технологий
- Python 3.12.9
- Pandas, NumPy
- Scikit-learn
- CatBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Основные этапы работы
- EDA и анализ данных
- Очистка данных и обработка выбросов
- Feature engineering
- Обучение и валидация моделей
- Подготовка submission-файла

## Структура проекта
Booking reviews (PJ-03)/  
├── competition.ipynb  
├── requirements.txt  
├── submission_final.csv  
├── README.md  
└── .gitignore  

```