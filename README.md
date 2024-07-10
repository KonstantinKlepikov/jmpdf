# jmpdf

Для парсинга таблиц используется [tabula-py](https://tabula-py.readthedocs.io/en/latest/getting_started.html#example), которому требуется java 8.x+. Перед установкой зависимостей првоерить jvm через `java -version`. Для разбора pdf в текст используется pymupdf.

Зависимости в requirements.txt ставить в виртуальное окружение так:

```sh
virtualenv -p python venv

# активировать venv

pip install -r requirements.txt
```

Разбор пдфки ведется в `/src`. Необходимо добавить файл спецификации в `data/example.pdf`. Основоной инструмент - jupyter notebooks.
