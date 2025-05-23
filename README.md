# Сегментация лёгких с использованием U-net++

Этот проект посвящён сегментации лёгких на медицинских снимках с помощью улучшенной архитектуры U-net++.

## Этапы работы

### ✅ Работа с данными
- Датасет загружен с помощью `opendatasets`
- Данные из папки "Normal" извлечены и подготовлены для обучения
- Выполнена предварительная обработка изображений и масок

### ✅ Обучение модели
- Реализована архитектура U-net++ на Keras/TensorFlow
- Подобраны оптимальные параметры модели
- Проведено обучение на подготовленных данных

### ✅ Проверка и визуализация
- Модель применена к тестовым данным
- Реализована визуализация для 10 снимков:
  - Оригинальное изображение
  - Истинная маска
  - Предсказанная маска

## Технологии
- Python
- TensorFlow/Keras
- U-net++ архитектура
- OpenDatasets для загрузки данных

## Результаты
Проект демонстрирует эффективное применение U-net++ для задачи сегментации лёгких на медицинских снимках с визуализацией результатов.
