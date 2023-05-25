# ABSA-GPT: Annotating CSV files via GPT models

This repository accompanies our paper to be presented at DH Benelux 2023, where we compare the performance of BERT Transformers and LLM (Large Language Models) in doing Aspect-Category-Opinion-Sentiment Quadruple Extraction. The example prompt is for aspect-based sentiment analyses (ABSA) in the domain of literary criticism, but can be adjusted ad lib. 

ChatGPT/GPT-3-based Aspect-Based Sentiment Analysis
## Usage

analysis_davinci.ipynb --> download https://github.com/mpangrazzi/absa_poc_pipeline and merge (prompt in gpt3.py)

openai_api_gpt-3.5-turbo_absa_def.ipynb --> standalone (prompts in notebook)

## Related work

Scikit-LLM: Sklearn Meets Large Language Models: https://github.com/iryna-kondr/scikit-llm (more elegant prompts for multiclass labels, but less hackeable)

## Citation

If you use our work, please cite it using the following BibTeX entry:
```
@inproceedings{01GZ6W6RDMEVXZRJXV4NFJGG9D,
  author = {Martens, Gunther and De Greve, Lore},
  title = {Annotation via LLM (Large Language Models) in Digital Literary Studies: beating (about) the bots?},
  booktitle = {DH Benelux 2023},
  year = {2023},
  url = {http://hdl.handle.net/1854/LU-01GZ6W6RDMEVXZRJXV4NFJGG9D},
  keywords = {chatgpt, LLM, sentiment mining, artificial intelligence, literary criticism, German studies, annotation},
  language = {eng},
}
```
