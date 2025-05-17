# DogCoach-agent

Інтерактивний помічник для тренування собак.

## Запуск без Docker

1. Встановіть залежності:
```
pip install -r requirements.txt
```

2. Створіть файл `.env` з вашим API ключем OpenAI:
```
OPENAI_API_KEY=your_api_key_here
```

3. Запустіть Streamlit додаток:
```
streamlit run dogcoach.py
```

## Запуск з Docker

1. Створіть файл `.env` з вашим API ключем OpenAI:
```
OPENAI_API_KEY=your_api_key_here
```

2. Запустіть контейнер через docker-compose:
```
docker-compose up -d
```

3. Додаток буде доступний за адресою: http://localhost:8501

Для зупинки:
```
docker-compose down
```