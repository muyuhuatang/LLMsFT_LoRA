# LLMsFT_LoRA
Efficient LLMs fine-tune technique LoRA replication. Here is one easy-to-run code and preliminary investigation report on utilizing the LoRA to foster the fine-tuning process of LLM (here is Llama2); interesting findings:
1. The LoRA technique can make fine-tuned llama2-7b much smarter and not just generate meaningless content for general questions
2. The LoRA technique can make fine-tuned llama2-13b-chat model very efficient, requiring less than 100 GB GPU memory, and just a few minutes to fine-tune 1 epoch on 1000 instances
3. LoRA fine-tuned llama2-13b-chat model can be close to ChatGPT-level performance in certain downstream tasks (Preliminary results right now).

Please find the 4-page report here: [https://github.com/muyuhuatang/LLMsFT_LoRA/blob/main/On_Investigation_of_LoRA_fine_tuning_on_LLMs__NLU_Performance.pdf](https://github.com/muyuhuatang/LLMsFT_LoRA/blob/main/report/On_Investigation_of_LoRA_fine_tuning_on_LLMs__NLU_Performance.pdf)

You can also find all my generation results in the \result folder here in this repo.


## Disclosure
The implicit hate speech dataset comes from the open-sourced NLP dataset, the paper's name is: $Latent Hatred: A Benchmark for Understanding Implicit Hate Speech$.

Financial information is manually collected as the sample in the website of: https://www.cnbc.com/quotes/BTC.CM=


## References
1. https://deci.ai/blog/fine-tune-llama-2-with-lora-for-question-answering/
2. https://www.datacamp.com/tutorial/fine-tuning-llama-2
3. https://arxiv.org/pdf/2309.13064
4. https://arxiv.org/abs/2403.12285
5. https://huggingface.co/datasets/gbharti/finance-alpaca?row=84
6. https://www.kaggle.com/datasets/notlucasp/financial-news-headlines?resource=download&select=cnbc_headlines.csv
7. https://arxiv.org/pdf/2402.06698
