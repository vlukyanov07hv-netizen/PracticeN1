## Что внутри?
| Файл | Описание |
|------|----------|
| `solution.ipynb` | Главный ноутбук с кодом |
| `data/code_corpus.json` | 200 фрагментов кода с описаниями |
| `data/eval_questions.json` | 25 тестовых вопросов с правильными ответами |
| `comparison_table.csv` | Таблица сравнения моделей |
| `tsne_visualization.png` | Визуализация эмбеддингов |
| `final_output.txt` | Краткий вывод по работе |

## Для запуска?
Требования:

● Python 3.12+

● Библиотеки: sentence-transformers, numpy, pandas, matplotlib, scikit-learn, tqdm

1. Клонируй репозиторий
```bash
git clone https://github.com/vlukyanov07hv-netizen/PracticeN1.git
```
```bash
cd PracticeN1
```
 2. Установи зависимости
```bash
pip install -r requirements.txt
```
 4. Запусти Jupyter
```bash
jupyter notebook solution.ipynb
```
## Что это?

Проект для учебной практики. Задача — найти лучшую модель для семантического поиска по фрагментам кода. Вместо поиска по точному совпадению текста используется поиск по смыслу (с помощью эмбеддингов). 

*Семантический поиск по коду - Сравнение моделей эмбеддингов для поиска по Python-коду.
