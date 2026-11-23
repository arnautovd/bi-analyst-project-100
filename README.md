# Дашборд конверсий


[![hexlet-check](https://github.com/arnautovd/bi-analyst-project-100/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/arnautovd/bi-analyst-project-100/actions)

Соберите в Jupyter Notebook данные из API, посчитайте конверсию и постройте графики

Учебный проект Хекслета: https://ru.hexlet.io/programs/bi-analyst


## Стек

- Python 3.12, Jupyter Notebook
- pandas, numpy, requests, python-dotenv
- matplotlib, seaborn, plotly

## Установка

```bash
git clone https://github.com/arnautovd/bi-analyst-project-100.git
cd bi-analyst-project-100
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
```

Переменные окружения (`.env`):

- `API_URL` — адрес API с данными (по умолчанию `https://data-charts-api.hexlet.app`)
- `DATE_BEGIN` — начало периода, `YYYY-MM-DD` (включительно)
- `DATE_END` — конец периода, `YYYY-MM-DD` (не включительно)
- `ADS_URL` — ссылка на CSV с рекламными кампаниями

## Использование

Выполнить ноутбук целиком одной командой:

```bash
jupyter execute analytics.ipynb
```

Интерактивная работа: `jupyter lab`.

---

<details>
<summary>Автоматические тесты Хекслета</summary>

Тесты запускаются на каждый коммит. За запуск отвечает файл `.github/workflows/hexlet-check.yml` — не удаляйте и не переименовывайте ни его, ни репозиторий.

</details>

## О Хекслете

[Хекслет](https://ru.hexlet.io/) — школа программирования: авторские программы обучения с практикой, поддержкой наставников и реальными проектами, которые остаются в резюме. Этот репозиторий — один из таких проектов.
