# Система определения негативных рецензий

*Статус проекта:*  
Проект завершен.

*Описание и цели:*  
Разработать систему фильтрации и категоризации рецензий фильмов, чтобы:  
- Научить модель автоматически обнаруживать негативные отзывы, используя набор данных рецензий фильмов IMBD с маркировкой полярности.

*Инструменты:*  
Pandas, Matplotlib, Numpy, Math, Seaborn, Sklearn, Tqdm, Spacy, Re, Nltk, Lightgbm, Pytorch

*Выводы:*  
- Лучшая оценка - f1_score = 0.86 (test) с использованием модели BERT.