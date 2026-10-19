# Портфолио

Я учусь на Python‑разработчика и развиваюсь в сторону backend: мне интересно проектировать логику, работать с данными и доводить проекты до рабочего результата. Ниже - два проекта с исходниками, инструкциями запуска и материалами для демонстрации.  
Ищу стажировку / junior‑позицию по Python backend (Москва/Чебоксары, возможна удалёнка).

**Контакты:** Telegram: @Solnyshko_love • Email: dparamonova638@gmail.com
**GitHub:** https://github.com/didi404-smart

---

## 1) BankProject — CLI для банковских транзакций + тесты

**Что сделано (результат):**
- Реализовано консольное приложение для загрузки операций из **JSON/CSV/XLSX** и формирования выборки транзакций по параметрам пользователя.
- Добавлены фильтрация/сортировка/поиск и отчёты по категориям, интеграция с внешним API конвертации валют, логирование.
- Ключевая функциональность покрыта **unit‑тестами** на `pytest` с `Mock/patch` (подмена внешних вызовов и проверка исключений).

**Стек:** Python, CLI, JSON/CSV/XLSX, pandas, pathlib, re, Counter, requests, dotenv, logging, pytest, mocking, Git.

**Ссылки:**
- Репозиторий: https://github.com/didi404-smart/BankProject

**Как запустить:**
```bash
git clone https://github.com/USERNAME/bankproject.git
cd bankproject

python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
# source .venv/bin/activate

pip install -r requirements.txt
python main.py
```
**Скриншоты:**
Пример запуска: assets/bankproject_cli.png
Результат pytest: assets/pytest.png
