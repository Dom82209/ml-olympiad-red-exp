# Задача 1 — SFT

Чистый стартовый репозиторий для задачи «Объяснятель».

Основной файл:

- `task1_sft_colab.ipynb`

Ноутбук:

- запускается сверху вниз в Colab/Kaggle с GPU;
- фиксирует `seed = 42`;
- обучает QLoRA 4-bit адаптер `Qwen/Qwen3-4B-Instruct-2507` на `kid_adult.jsonl`;
- генерирует ответы на `public_test_style.jsonl` с `do_sample=False`;
- печатает `Task 1 SFT P_simple = ...`;
- печатает букву интервала.

Данные для первой задачи лежат в `task_data/`.
