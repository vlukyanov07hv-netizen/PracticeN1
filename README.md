## Что внутри?
| Файл | Описание |
|------|----------|
| `solution.ipynb` | Главный ноутбук с кодом |
| `code_corpus.json` | 200 фрагментов кода с описаниями |
| `eval_questions.json` | 25 тестовых вопросов с правильными ответами |
| `comparison_table.csv` | Таблица сравнения моделей |
| `tsne_visualization.png` | Визуализация эмбеддингов |
| `final_output.txt` | Краткий вывод по работе |

## Для запуска?
__Требования:__

● Python 3.12+

● Библиотеки: sentence-transformers, numpy, pandas, matplotlib, scikit-learn, tqdm

__1. Клонируй репозиторий__
```bash
git clone https://github.com/vlukyanov07hv-netizen/PracticeN1.git
```
__2. Перейди в репозиторий__
```bash
cd PracticeN1
```
__3. Подготовь данные__

 Шаг№1 
```bash
mkdir data
```
 Шаг№2 
 
 Перемести файлы `code_corpus.json` и `eval_questions.json` в `data`
 
● для Windows:
 ```bash
 move code_corpus.json data
 ```
 ```bash
 move eval_questions.json data
 ```

● для macOS/Linux:
 ```bash
 mv code_corpus.json data
 ```
 ```bash
 mv eval_questions.json data
 ```
__4. Установи и активируй venv__

● для macOS/Linux:
```bash
 python3 -m venv venv
 ```
```bash
 source venv/bin/activate
 ```


● для macOS/Linux:
```bash
 python3 -m venv venv
 ```
```bash
 source venv/bin/activate
 ```
__5. Установи зависимости__
```bash
pip install -r requirements.txt
```
__6. Запусти Jupyter__
```bash
jupyter notebook solution.ipynb
```
__7. Перезапусти Kernel и запусти все ячейки__
## Что это?

Проект для учебной практики. Задача — найти лучшую модель для семантического поиска по фрагментам кода. Вместо поиска по точному совпадению текста используется поиск по смыслу (с помощью эмбеддингов). 

*Семантический поиск по коду - Сравнение моделей эмбеддингов для поиска по Python-коду.
