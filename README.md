# Docs as code

Учебный docs-as-code проект: документация ИИ-проекта **«Классификатор изображений»** —
сервиса, который определяет категорию объекта на загруженной фотографии.

Автор: Юрий Фатеев

## Структура

```
docs/
├── index.md
├── project/          # Практикум 2: описание, требования, диаграммы
│   ├── overview.md
│   ├── requirements.md
│   └── diagrams.md
├── api/              # Практикум 3: OpenAPI-спецификация
│   ├── index.md
│   ├── swagger.md
│   ├── swagger.html
│   └── openapi.yaml
└── ml/               # Практикум 4: документация ML-модели
    ├── model-card.md
    ├── dataset.md
    └── risks.md
screenshots/          # скриншоты сайта, диаграмм и Swagger
mkdocs.yml
```

## Запуск

```bash
pip install -r requirements.txt
mkdocs serve
```

Сайт откроется по адресу <http://127.0.0.1:8000>.
