# judgement

Здесь лежат файлы с кодом для анализа уголовных приговоров первой инстанции

- `metadata_extractor.py` выделяет именованные сущности
- `classifier.py` делит на смысловые части

В папке `models`:
- `finalized_parts_clf.sav` -- модель-классификатор частей
- `segmenter.pk` -- модель сегментации на предложения