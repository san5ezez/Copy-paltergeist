# Copy-paltergeist

Интерактивный прототип интерфейса Poltergeist (а не просто статический лендинг).

## Что уже работает

- Панель модератора слева + live preview справа (16:9, под OBS Browser Source).
- Управление **Lower Third**: заголовок/описание + show/hide.
- Управление **Scoreboard**: названия команд, счет, show/hide.
- Управление **Timer**: show/hide, start/pause.
- **Telestrator**: рисование поверх preview (цвет/толщина пера, очистка).

## Запуск

```bash
python3 serve.py
```

Открыть в браузере:

- `http://127.0.0.1:8000`

Можно указать хост/порт:

```bash
python3 serve.py --host 0.0.0.0 --port 8080
```

## Быстрый fallback без скрипта

```bash
python3 -m http.server 8000
```
