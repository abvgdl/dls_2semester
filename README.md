# Machine Learning Homeworks - MIPT DLS 2nd Semester (Natural Language Processing)

Репозиторий содержит домашние задания курса **Deep Learning School (МФТИ)** за 2 семестр: задачи по **NLP** и **LLM**.

## Tech Stack

`PyTorch`, `NumPy`, `Pandas`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `NLTK`, `Hugging Face Datasets`, `Gensim`, `tqdm`

## Содержание репозитория

| Файл/Папка | Описание задачи | Технологии и методы |
|---|---|---|
| `hw1_simple_embeddings.ipynb` | Семантическая близость и ранжирование текстов на основе эмбеддингов | Word Embeddings (Gensim), усреднение векторов предложений, cosine similarity, Learning-to-Rank метрики (DCG/NDCG/Hits) |
| `hw2_text_classification.ipynb` | Нейросетевая классификация текстов (sentiment/topic classification) | PyTorch, tokenization, RNN/GRU/LSTM, multi-layer recurrent architectures, Adam optimizer, accuracy evaluation |
| `hw3_language_modelling.ipynb` | Обучение языковой модели и сравнение экспериментов по перплексии | Word-level language modeling, PyTorch, DataLoader pipeline, training loop/evaluate loop, perplexity, экспериментальный анализ архитектур |
| `README.md` | Описание репозитория, структуры и используемого стека | Markdown |

## Итоговые метрики

| Homework | Лучшая итоговая метрика | Комментарий |
|---|---:|---|
| `hw1_simple_embeddings.ipynb` | **DCG@1 = 0.414**, **Hits@1 = 0.414** | Лучший результат среди показанных вариантов ранжирования в ноутбуке |
| `hw2_text_classification.ipynb` | **Accuracy = 91.90%** | Лучший зафиксированный результат в логах обучения |
| `hw3_language_modelling.ipynb` | **Eval Perplexity = 95.20** | Минимальная валидационная перплексия среди проведённых экспериментов |

