# important-polls
* Telegram бот с LLM для генерации опросов.
* Модель - [ai-forever/rugpt3medium_based_on_gpt2](https://huggingface.co/ai-forever/rugpt3medium_based_on_gpt2) (355M параметров).
* Finetune на записях сообществ `vso_1`, `hbtvv`, `2oprosa`, `public180811191`. Сбор и отчистка датасета есть в collect и clear файлах. Обучалась 3 эпохи
* Опросы автоматически постятся в [телеграм канал](https://t.me/polls4life).
* К каждому опросу генерируются картинки с помощью Kandinsky от Сбера.
* /dev - режим со сравнением двух опросов для сбора статистики и дальнейшего улучшения модели.
