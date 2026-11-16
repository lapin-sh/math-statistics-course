# Специальные разделы математической статистики

Учебные работы Максима Лапина по курсу магистратуры МИФИ и Яндекс Практикума. [Силлабус курса](https://practicum.yandex.ru/learn/higher-data-analytics/courses/143f322a-f5c5-48df-943c-621a37fdb7e9/sprints/1079512/topics/f5cbc891-053a-4d26-9a8f-3eae3eaa9997/lessons/58dedf29-8e21-4ea8-9e3b-0fbca874c63e/)

## Ноутбуки

| Работа | Содержание |
| --- | --- |
| [ДЗ №1. Применение статистических критериев](homework/01-statistical-tests.ipynb) | Доверительные интервалы, проверка средних и дисперсий, дисперсионный анализ, A/B-тест для долей |
| [ДЗ №2. Корреляция и регрессия](homework/02-correlation-and-regression.ipynb) | Корреляция, линейная и множественная регрессия, градиентный спуск, бутстрэп и диагностика остатков. Вывод о значимости предикторов уточнён после ревью |
| [Практика. Вероятностные распределения](practice/02-probability-distributions.ipynb) | Плотности, гистограмма с теоретической кривой, вероятности биномиального распределения, круговая диаграмма и регрессия на сгенерированных данных |

## Повторный запуск

Используйте Python 3.12. Из корня репозитория выполните команды ниже.

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

В PowerShell используйте `.\.venv\Scripts\Activate.ps1` для активации среды.

Для ДЗ №2 скачайте [исходный датасет курса](https://drive.google.com/file/d/1v05O3zK5m_29SKgY36Nr4_OG0nqZZad4/view?usp=drive_link) и положите его в `homework/practical_module_dataset.csv`. В macOS и Linux это можно сделать из корня репозитория.

```sh
curl --fail --location 'https://drive.google.com/uc?export=download&id=1v05O3zK5m_29SKgY36Nr4_OG0nqZZad4' \
  --output homework/practical_module_dataset.csv
```

Откройте нужный ноутбук в JupyterLab и выполните все ячейки сверху вниз. Сохранённые результаты и графики также доступны при просмотре файлов на GitHub.
