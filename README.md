# LLMEvaluation
Found out that using A100 and V100 on Vicuna and Llama2 have a different result, while other model such as Falcon doesn't has such question.
The results are here.
![image](https://github.com/Paulyang80/LLMEvaluation/assets/58577554/f0d5022a-0123-4938-af1d-6a3252588de7)

## Experiment
Running the experiment on Google Colab Pro +

## Model Evaluation
We use [four LLM benchmarks](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) to evaluate the model.
1. Hellaswag: acc
2. Truthfulqa_mc: mc1, mc2
3. Arc_challenge: acc 
4. MMLU(HendrycksTest): Average score of all test acc.
