# NLP-Dialogue-Summarization
### NLP project on Dialogue Summarization using [FLAN-T5](https://huggingface.co/google/flan-t5-base)


![image](https://github.com/user-attachments/assets/5c09db23-b234-4661-917f-688e2d57935e)


In the notebook, I fine-tuned an existing LLM from Hugging Face for enhanced dialogue summarization. I made use of the [FLAN-T5](https://huggingface.co/docs/transformers/model_doc/flan-t5) model, which provides a high quality instruction tuned model and can summarize text out of the box. To improve the inferences, explored a full fine-tuning approach and evaluated the results with ROUGE metrics. Then I performed [Parameter Efficient Fine-Tuning (PEFT)](https://github.com/huggingface/peft), evaluated the resulting model and saw that the benefits of PEFT outweigh the slightly-lower performance metrics.

This is part of the Deeplearning.ai Course on [Generative AI with LLMs](https://www.coursera.org/learn/generative-ai-with-llms) in Collaboration with AWS


## Technologies Used:
- Language: Python

- Dataset:
  - [Dialogsum](https://huggingface.co/datasets/knkarthick/dialogsum)
- Model:
  - [FLAN-T5-base](https://huggingface.co/google/flan-t5-base)
- Fine Tuning:
  - [PEFT](https://github.com/huggingface/peft)
- Other Technologies:
  - AWS
  - Google Colab
  - GPU
  - Transformers
  - Pytorch
  - Huggingface Models
