# Анализ музыкальных треков (Spotify)

Проект по изучению аудио-характеристик музыкальных треков: популярности, жанров, длительности и т.д.

## Структура проекта

- `data/spotify_tracks.csv` — исходные данные
- `notebooks/exploratory_analysis_music.ipynb` — EDA в Jupyter
- `images/` — графики и визуализации
- `requirements.txt` — зависимости проекта

## Анализ включает:
- Топ жанров по количеству треков
- Распределение популярности
- Связь между energy и популярностью
- Связь danceability и valence
- Средняя длительность треков
- Популярность в мажоре и миноре

## Используемые модули:
- Python: `pandas`, `matplotlib`, `seaborn`
- Jupyter Notebook
- Графики: bar, hist, scatter

## Запуск
```bash
pip install -r requirements.txt
jupyter notebook notebooks/exploratory_analysis_music.ipynb
```