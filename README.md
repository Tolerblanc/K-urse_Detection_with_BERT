# K-urse_Detection_with_BERT

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)  ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

## Overview
**K-urse_Detection_with_BERT** : Korean Cursing expression Detection with fine-tuned klue_BERT

This is the KWU "text mining" output for the first semester of 2023.

See Project Overview Here! : [Notion(Korean)](https://www.notion.so/tolerblanc/4d70c776b3f74dbe8e03a38ccda27fbb?pvs=4)

See this model on HuggingFace 🤗 : [Link](https://huggingface.co/Tolerblanc/klue-bert-finetuned
)

## Evaluation
- Comparison Model is [here](https://github.com/JminJ/Bad_text_classifier)
- Used [2runo's Curse-detection-data](https://github.com/2runo/Curse-detection-data)

| Model/Metric | Accuracy | Precision | Recall | F1 Score |
| --- | --- | --- | --- | --- |
| Comparison(Electra base) | 0.81 | 0.69 | **0.87** | **0.77** |
| klue-BERT base(Our best result) | **0.83** | **0.76**** | 0.75 | 0.75 |

- Used Youtube Comments

| Model/Metric | Accuracy | Precision | Recall | F1 Score |
| --- | --- | --- | --- | --- |
| Comparison(Electra base) | 0.77 | 0.52 | **0.90** | 0.66 |
| klue-BERT base(Our best result) | **0.89** | **0.75** | 0.80 | **0.78** |

## Demo with HuggingFace's Space 🤗
Try Demo Here! [Go to HuggingFace Space](https://huggingface.co/spaces/Tolerblanc/Demo_Kurse_detection)

## Reference
- Smilegate-AI's Korean Unsmile Dataset : [Link](https://huggingface.co/datasets/smilegate-ai/kor_unsmile)
- JeanLee's K-MHaS Dataset and Paper : [Link](https://huggingface.co/datasets/jeanlee/kmhas_korean_hate_speech)
- KLUE(Korean Language Understanding Evaluation) BERT : [Link](https://github.com/KLUE-benchmark/KLUE)
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding : [Link](https://arxiv.org/abs/1810.04805)
- 2runo's Curse Detection Dataset : [Link](https://github.com/2runo/Curse-detection-data)
- JminJ's Bad Text Classifier : [Link](https://github.com/JminJ/Bad_text_classifier)
