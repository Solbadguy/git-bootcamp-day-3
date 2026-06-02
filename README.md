# taskmanager
Учебный CLI-менеджер задач на Python. Позволяет добавлять задачи, просматривать список и помечать их как выполненные.  
Минимальный API в `tasks.py`: `add_task(title)`, `list_tasks()`.

## 📑 Оглавление
- [Описание](#описание)
- [Запуск](#запуск)
- [Установка](#установка)
- [TODO](#todo)
- [Структура-проекта](#структура-проекта)
- [Лицензия](#лицензия)

## Описание
Минимальный учебный менеджер задач, работающий через Python API.

## Запуск
```bash
python3 -c "import tasks; tasks.add_task('купить хлеб'); tasks.list_tasks()"
```

## Установка
```bash
git clone https://github.com/Solbadguy/git-bootcamp-day-3
cd git-bootcamp-day-3
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## TODO
- [ ] Добавить удаление задач
- [ ] Добавить отметку о выполнении
- [ ] Добавить хранение в файле или SQLite
- [ ] Добавить CLI‑флаги (--add, --list, --done)
- [ ] Написать тесты

## Структура проекта
<details><summary>Показать структуру</summary>

```text
taskmanager/
├── tasks.py
├── README.md
└── requirements.txt
```

</details>

## Лицензия
_MIT — https://opensource.org/licenses/MIT_
