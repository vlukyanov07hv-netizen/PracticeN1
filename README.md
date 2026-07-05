## Что внутри?
| Файл | Описание |
|------|----------|
| `solution.ipynb` | Главный ноутбук с кодом |
| `data.zip/code_corpus.json` | 200 фрагментов кода с описаниями |
| `data.zip/eval_questions.json` | 25 тестовых вопросов с правильными ответами |
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
2. Подготовь данные

 Шаг.1  Распакуй `data.zip`
 
 Шаг.2  Создай папку `data` внутри клонированного репозитория
 
 Шаг.3  Перемести файлы `code_corpus.json` и `eval_questions.json` в `data`
 
3. Перейди в репозиторий
```bash
cd PracticeN1
```
4. Запусти Jupyter
```bash
jupyter notebook solution.ipynb
```
5. Перезапусти Kernel и запусти все ячейки
## Что это?

Проект для учебной практики. Задача — найти лучшую модель для семантического поиска по фрагментам кода. Вместо поиска по точному совпадению текста используется поиск по смыслу (с помощью эмбеддингов). 

*Семантический поиск по коду - Сравнение моделей эмбеддингов для поиска по Python-коду.
