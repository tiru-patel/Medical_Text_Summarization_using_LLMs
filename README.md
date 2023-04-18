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

## Results Obtained
<p align="justify">
From the result, it is observed that GPT-4 outperforms the summarization models in their niche
tasks and even without fine-tuning. Medical summarization is very technical in nature and zero-shot
prediction providing competitive results reaffirms belief in the generalized nature of their learning.
The trends are similar to GPT-4 performance in medical competitive tests of UCMLE, thus again
highlighting the complex data analysis capabilities of such LLMS. As far as the comparative study
of this work is considered It has been proven that very large models which are zero-shot learners
give comparable or better performance than the fine-tuned models. Further, it has been observed that
smaller models are marginally poor than the comparatively very large models. So these can point to
future work, which can analyze the computational cost, and accuracy analysis based on the number
of parameters. Even further focus on comparing the models on these attributes by fine-tuning them
with larger data sets. And thus inspecting the marginal utility of spending extra computational cost.
</p>

## Files Structure
<p align="justify">
1. <b>BART_BASE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of BART-Base Model<br/>
2. <b>T5_BASE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of T5-Base Model<br/>
3. <b>PEGASUS_LARGE_Medical_Text_Summarization.ipynb</b>: Fine-tuning of Pegasus-Large Model<br/>
4. <b>LLMs_evaluation.ipynb</b>: Testing and Inferencing on the test set for Fine-tuned and GPT Models
</p>

