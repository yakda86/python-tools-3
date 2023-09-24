# Фитнес-трекер

Пример запуска на Windows:
```
python main.py
```

Пример запуска на Linux/macOS:
```
python3 main.py
```

Для запуска тестов нужно развернуть и активировать виртуальное окружение:
```
# Команда для Windows:
python -m venv venv

# Команда для Linux и macOS:
python3 -m venv venv

# Команда для Windows:
source venv/Scripts/activate

# Для Linux и macOS:
source venv/bin/activate
```

Тесты запускаются через `pytest`. Нужная версия указана в `requirements.txt`, установить её можно так:

```
pip install -r requirements.txt
```

Запускаются тесты так:

```
pytest tests.py
```
