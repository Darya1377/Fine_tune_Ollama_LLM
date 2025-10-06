# LLM Fine tuning

Код для файтюнинга модели на датасете, сгенерированным нейросетью на парсинг HTML-запросов (json_ectraction_dataset.json)

## Использование LoRA и загрузка модели в Ollama
Чтобы загрузить модель в Ollama, лучше создать отдельную папку с моделью model.gguf и создать Makefile (в Makefile в первой строке нужно указать название модели)
И вызывать следующие команды из директории, где находится модель и Makefile:
```
ollama create html-model
```
```
ollama run html-model
```
