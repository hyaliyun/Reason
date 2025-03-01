Reason
Natural Reasoning dataset

crypto ?OpenAI deepseekgrok 

🚀 NaturalReasoning Dataset Overview
Explore the NaturalReasoning dataset, a large-scale collection of 1.1M high-quality, challenging reasoning questions backtranslated from DCLM and FineMath pretraining corpora. Designed to foster research on training strong LLM reasoners, it includes deduplicated and decontaminated questions from benchmarks like MATH, GPQA, MMLU-Pro, and MMLU-STEM.

Download Dataset
📊 Reference Answer Statistics
In the 1.1M subset: 18.29% of questions lack a reference answer, 9.71% have single-word answers, 21.58% have short answers, and 50.42% feature long reference answers. Answers are extracted from original pretraining corpora where possible, with model-generated responses from Llama3.3-70B-Instruct provided.

View Details
📈 Scaling Curve Insights
Training on NaturalReasoning outperforms other datasets when fine-tuning the Llama3.1-8B-Instruct model. Performance is measured across three benchmarks—MATH, GPQA, and MMLU-Pro—demonstrating superior scaling effects for enhanced reasoning capabilities.

Learn More
🛠️ Dataset Composition
Questions are sourced from DCLM and FineMath, backtranslated, and cleaned to ensure quality. The dataset avoids overlap with popular benchmarks and includes reference answers where available, supplemented by Llama3.3-70B-Instruct-generated responses for research flexibility.

Explore Composition
🔭 Dataset Limitations
While comprehensive, 18.29% of questions lack reference answers, and model-generated responses may require validation. Researchers should verify results for critical applications, as the dataset is intended to support experimentation rather than serve as a definitive ground truth.

Understand Limitations
