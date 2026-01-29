# Screen-Time-Stress-and-Mental-Well-being-A-Python-Analysis-NumPy-Pandas-Matplotlib
Analyzing Screen Time’s Impact on Stress and Mental Health with Python (NumPy, Pandas, Matplotlib)

# Анализ влияния экранного времени на уровень стресса и психическое благополучие

Данный проект представляет собой учебную работу по анализу данных с использованием библиотек Python: **NumPy**, **Pandas** и **Matplotlib**.  
Цель — исследовать взаимосвязь между количеством времени, проведённого за экранами, уровнем стресса и индексом психического благополучия.

## Данные

- Источник: синтетический датасет `ScreenTime_vs_MentalWellness.csv`
- Столбцы:
  - `age` — возраст
  - `gender` — пол
  - `occupation` — род занятий
  - `screen_time_hours` — время у экрана (часы/день)
  - `stress_level_0_10` — уровень стресса (шкала 0–10)
  - `mental_wellness_index_0_100` — индекс психического благополучия (шкала 0–100)
  - `timestamp` — временная метка

## Технологии

- Python 3.x
- Библиотеки: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Обработка пропущенных значений
- Визуализация: временные ряды, диаграммы рассеяния, boxplots
- Группировка, фильтрация, расчёт корреляций

## Что реализовано

- Предварительная обработка данных
- Подсчёт уникальных значений
- Расчёт корреляции между числовыми признаками
- Фильтрация по нескольким критериям
- Группировка с агрегацией (среднее, std)
- Построение графиков:
  - временной ход показателей,
  - scatter plot с цветовым разделением по категориям,
  - boxplot по группам

##  Запуск

Вы можете запустить этот ноутбук прямо в Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VeronikaKolimova/Screen-Time-Stress-and-Mental-Well-being-A-Python-Analysis-NumPy-Pandas-Matplotlib/blob/main/L_02.ipynb)

## Структура

- `L_02.ipynb` — основной Jupyter Notebook
- `ScreenTime_vs_MentalWellness.csv` — датасет

## Автор

Кулак Вероника
