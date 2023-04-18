## About the Project
<p align="justify">
Due to the rapid expansion of medical literature, keeping pace with the latest
research and clinical guidelines has become more challenging for healthcare pro-
fessionals. To overcome this challenge, effective text summarization is crucial for
improving access to knowledge, enhancing clinical decision-making, and ultimately
benefiting patient outcomes. In this study, a medical text summarization system
that employs large language models (LLMs) is fine-tuned and evaluated with the
objective of generating precise, logical, and brief summaries of medical literature,
emphasizing clinical relevance and ease of understanding. The projects focus on evaluating the
performance of GPT3, GPT4 and the fine-tuned T5, BART and Pegasus model
trained on the standard PubMed dataset using standard evaluation metrics.
</p>

## Evaluation Metrics
<p align="justify">
The standard evaluation metrics used for summarization tasks include ROUGE scores, METEOR and
Bert Scores and are used for evaluation purpose. The above mentioned metrics captures the structural
and semantic similarity between the generated and reference summary. Other metrics also used for
evaluation include BLEU score and SaceBLEU.
</p>

## Files Structure
<p align="justify">
1. <b>BART_BASE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of BART-Base Model<br/>
2. <b>T5_BASE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of T5-Base Model<br/>
3. <b>PEGASUS_LARGE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of Pegasus-Large Model<br/>
4. <b>LLMs_evaluation.ipynb</b>: Testing and Inferencing on the test set for Fine-tuned and GPT Models
</p>

