# NER-approaches
## About this project

- Основная цель исследования:
    - Цель — сравнение различных подходов в задаче NER для выявления их преимуществ и недостатков.
    - Объект исследования — основные подходы к решению задачи NER:
        - dictionary-based
        - rule-based (Natasha)
        - machine learning-based (CRF)
        - deep leaning-based (fine-tuned BERT)
- Актуальность темы:
    - Выбранная тема актуальна, так как из-за увеличения объемов текстовых данных возрастает потребность в автоматизации извлечения структурированной информации. Сравнение различных подходов к поиску именованных сущностей позволяет определить наиболее эффективные методы для конкретных задач и условий.
    - Это имеет важное значение для многих областей:
        - Поисковые системы
        - Журналистские расследования
        - Биоинформатика
        - Мониторинг социальных сетей
        - Контекстная реклама
- Существующие исследования в этой области:
    - Существуют исследования, по разработке и оптимизации нейронных сетей для решения задач NER, а также по сравнению эффективности моделей ML и DL при решении специфичных задач NER.
- Гипотезы:
    - Подходы, использующие machine learning и deep learning окажутся более гибкими к разным типам задач.
    - Rule-based и dictionary-based подходы будут эффективны в конкретных типах задач, но в остальных задачах они будут уступать другим подходам.
- Что известно по данной теме?
    - Основные исследования: Существуют исследования, по разработке и оптимизации нейронных сетей для решения задач NER, а также по сравнению эффективности моделей ML и DL при решении специфичных задач NER.
    - Пробелы и ограничения: требуется адаптировать все выбранные подходы к решению разных типов задач.
- Каковы исходные гипотезы и исследовательские вопросы?
    - Исходные гипотезы: Предполагается, что подходы, использующие ML и DL будут иметь более высокую точность на нестандартных наборах данных.
    - Исследовательские вопросы:
        - Каковы ключевые различия между dictionary-based, rule-based, machine learning-based, deep leaning-based в NER?
        - В каких задачах dictionary-based и rule-based превосходят ML и DL подходы?
        - Как различные подходы справляются с разными языками и терминологией, специфичной для предметной области? Используемые датасеты
- Используемые датасеты
  - CONLL-2003
  - Collection3
  - BC5CDR