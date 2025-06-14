# Multi-Label Emotion Classification Using Fine-Tuned RoBERTa Transformer

*Ranked 31st (Track A) & 17th (Track B) @ SemEval-2025 Task 11*

---

## Overview  

This repository contains our code for two emotion analysis tasks in English text:  
1. **Track A**: Multi-label emotion classification (Joy, Sadness, Fear, Anger, Surprise, Disgust)  
2. **Track B**: Emotion intensity prediction (0-3 scale)  

## Key achievements:  

	- **Macro F1-score of 0.75** for multi-label classification  
	- **Pearson correlation of 0.75** for intensity prediction  
	- Fine-tuned RoBERTa-large transformer for both tasks  

---

## Pre-requisites

Make sure you install all the requirements from the requirements.txt file provided

```
pip install -r requirements.txt
```

## Usage

Download the colab notebook file given above and the datasets 

## Results

Track A (Classification)

|Emotion	|Precision	|Recall	|F1-score|
|---------------|---------------|-------|--------|
|Joy	        |0.82	        |0.78	|0.80    |
|Sadness	|0.81	        |0.76	|0.78    |
|Fear	        |0.85	        |0.82	|0.84    |
|Anger	        |0.68	        |0.65	|0.66    |

---

Track B (Intensity Prediction)

|Emotion   	|Pearson's Correlation|
|---------------|---------------------|
|Joy		|0.78                 |
|Sadness	|0.79                 |
|Fear		|0.73                 | 

## Citation

```bibtex
@inproceedings{vijaykarthickvaidyanathan2025multilabel,
  title={Multi-Label Emotion Classification Using Fine-Tuned RoBERTa-Large Transformer},
  author={Vijay Karthick V, Srihari V K, Mugilkrishna D U and Saritha M},
  booktitle={Proceedings of SemEval-2025},
  year={2025}
}
```

## Note

This paper is in the process of publishing and the official link will be updated soon. However, you can still access our paper with the local pdf copy provided in the repo

