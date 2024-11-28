# ABSA-GPT: Annotating CSV files via GPT models

This repository accompanies our paper presented at DH Benelux 2023, where we compare the performance of BERT Transformers and LLM (Large Language Models) in doing Aspect-Category-Opinion-Sentiment Quadruple Extraction. The example prompt is for aspect-based sentiment analyses (ABSA) in the domain of literary criticism, but can be adjusted ad lib. 

ChatGPT/GPT-3-based Aspect-Based Sentiment Analysis
## Usage
<i>Please note that the scripts correspond to the state of affairs of May 2023 (i.e. prior to arrival of GPT3-turbo, system prompt/roles, file upload, OSS LLM, GPT-4's response_format type json_object etc.). I would not recommend using the scripts without alterations, for the simple reason that the context size of GPT now allows for larger batch sizes; running it row by row is more expensive.</i>

analysis_davinci.ipynb --> download https://github.com/mpangrazzi/absa_poc_pipeline and merge (prompt in gpt3.py)

openai_api_gpt-3.5-turbo_absa_def.ipynb --> standalone (prompts in notebook)

## Related work

Our full pipeline (May 2024) is to be found here: https://github.com/GhentCDH/CLSinfra . Recommended if you want to finetune models (also free LLM). 

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
## Credits

This repository borrows from https://github.com/mpangrazzi/absa_poc_pipeline. Pangrazzi published his proof of concept for doing ABSA via gpt-3 on Sep 9, 2022, prior to the actual public release of ChatGPT, go figure!
