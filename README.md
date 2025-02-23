# unsloth-challenge

## Task D

- Tool Calling example [notebook](./Llama3_1_(8B)_Tool_Calling.ipynb)
- VLMs image resizing: [fork](https://github.com/oliveirabruno01/unsloth/tree/patch-max-image-size).
  - Colab [notebook](https://colab.research.google.com/drive/10BuVcefoVbAx1OIDtV6KvhboehQCOc3R?usp=sharing)
  - Patch Trainers constructors to add a resize step if `UnslothVisionDataCollator` is present.
- GGUF Vision support **[INCOMPLETE]**: [fork](https://github.com/oliveirabruno01/unsloth/tree/vlm-gguf-save)
