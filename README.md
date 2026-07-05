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
**Требования:**

● Python 3.12+

● Библиотеки: sentence-transformers, numpy, pandas, matplotlib, scikit-learn, tqdm

**1. Клонируй репозиторий**
```bash
git clone https://github.com/vlukyanov07hv-netizen/PracticeN1.git
```
**2. Перейди в репозиторий**
```bash
cd PracticeN1
```
**3. Подготовь данные**

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
**4. Установи и активируй venv**

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
**5. Установи зависимости**
```bash
pip install -r requirements.txt
```
**6. Запусти Jupyter**
```bash
jupyter notebook solution.ipynb
```
**7. Перезапусти Kernel и запусти все ячейки**
## Что это?

Проект для учебной практики. Задача — найти лучшую модель для семантического поиска по фрагментам кода. Вместо поиска по точному совпадению текста используется поиск по смыслу (с помощью эмбеддингов). 

*Семантический поиск по коду - Сравнение моделей эмбеддингов для поиска по Python-коду.
