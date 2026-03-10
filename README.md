# Awesome AI Benchmarks & Evaluation [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of evaluation tools, benchmark datasets, leaderboards, frameworks, and resources for assessing model performance across reasoning, safety, robustness, multimodality, RAG, LLMs, and traditional machine learning tasks.

## Contents

- [General LLM Benchmarks](#general-llm-benchmarks)
- [Reasoning & Math](#reasoning--math)
- [Multimodal Benchmarks](#multimodal-benchmarks)
- [RAG Benchmarks](#rag-benchmarks)
- [Safety & Robustness](#safety--robustness)
- [Evaluation Frameworks](#evaluation-frameworks)
- [Datasets](#datasets)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## General LLM Benchmarks

- [HELM](https://crfm.stanford.edu/helm/latest/) – Holistic evaluation of LLMs across dozens of tasks and domains.
- [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) – Standardized benchmarking suite for language models.
- [OpenLLM Leaderboard (HuggingFace)](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) – Public leaderboard for open-source LLM performance.
- [BIG-Bench](https://github.com/google/BIG-bench) – Broad set of challenging tasks for evaluating model generalization.
- [MT-Bench](https://github.com/lm-sys/FastChat) – Multi-turn chat interaction benchmark.
- [AlpacaEval](https://github.com/tatsu-lab/alpaca_eval) – Automatic evaluation of instruction-following models.

## Reasoning & Math

- [GSM8K](https://github.com/openai/grade-school-math) – Benchmark for math reasoning at grade-school level.
- [MATH](https://github.com/hendrycks/math) – Extensive dataset of high school and competition math problems.
- [AIME Bench](https://github.com/derivationlog/AIME-2024) – Benchmark based on American Invitational Mathematics Examination questions.
- [ARC (Abstraction & Reasoning Corpus)](https://github.com/fchollet/ARC) – Tests generalization and abstraction capabilities.
- [AGIEval](https://github.com/ruixiangcui/AGIEval) – Benchmarks for human-style exams and reasoning.

## Multimodal Benchmarks

- [MMBench](https://github.com/open-mmlab/mmbench) – Large benchmark for vision–language reasoning.
- [COCO Captions & VQA](https://visualqa.org/) – Standard dataset for VQA tasks.
- [Flickr30k](https://www.kaggle.com/datasets) – Image–text benchmark for captioning and retrieval.
- [ImageNet](https://image-net.org/) – Core image classification benchmark still used for comparison.
- [LAION Benchmarks](https://laion.ai/blog/) – Evaluation datasets for multimodal embeddings and retrieval.
- [Video Question Answering Benchmarks](https://github.com/topics/video-question-answering) – For video–text reasoning.
  
## RAG Benchmarks

- [RAGAS](https://github.com/explodinggradients/ragas) – Comprehensive metrics for evaluating retrieval-augmented generation.
- [BEIR](https://github.com/beir-cellar/beir) – Retrieval benchmark widely used to test search quality in RAG systems.
- [FiQA / TREC Variants](https://trec.nist.gov/) – Evaluation datasets for information retrieval tasks.
- [Natural Questions (NQ)](https://ai.google.com/research/NaturalQuestions) – Large dataset for retrieval + QA evaluation.
- [HotpotQA](https://hotpotqa.github.io/) – Multi-hop question answering benchmark.

## Safety & Robustness

- [HarmBench](https://github.com/centerforaisafety/HarmBench) – Safety and harm classification benchmark.
- [SafetyBench](https://github.com/centerforaisafety/SafetyBench) – Benchmark suite for safety testing.
- [ToxiGen](https://github.com/microsoft/Counterfit) – Dataset for toxic or harmful content detection.
- [Red Team Prompt Datasets](https://github.com/topics/jailbreak-prompts) – Collections of prompts to stress-test model alignment.
- [RobustBench](https://github.com/RobustBench/robustbench) – Leaderboard of robust classification models.
- [AdversarialNLI](https://github.com/facebookresearch/anli) – Dataset for robustness in natural language inference.

## Evaluation Frameworks

- [OpenAI Evals](https://github.com/openai/evals) – Evaluation framework for custom metrics and tasks.
- [TruLens](https://github.com/truera/trulens) – Observability and feedback evaluation for LLM apps and RAG.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) – Open-source toolkit for LLM/RAG evals and trace analysis.
- [LightEval](https://github.com/hazyresearch/lighteval) – Fast LLM evaluation pipeline.
- [Evalchemy](https://github.com/zphang/evalchemy) – Lightweight framework for running LLM benchmarks.
- [Weights & Biases Evaluation](https://wandb.ai) – Model comparison and metric visualization tools.

## Datasets

- [TruthfulQA](https://github.com/sylinrl/TruthfulQA) – Benchmark for truthfulness in open-ended QA.
- [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) – Reading comprehension dataset.
- [BoolQ](https://github.com/google-research/language/tree/master/language/boolq) – Yes/no question dataset.
- [SuperGLUE](https://super.gluebenchmark.com/) – General NLU evaluation suite.
- [MultiRC](https://cogcomp.seas.upenn.edu/multirc/) – Multi-sentence reasoning benchmark.
- [WikiQA](https://www.microsoft.com/en-us/download/details.aspx?id=52419) – QA benchmark used in retrieval + QA systems.
- [CommonSenseQA](https://www.tau-nlp.org/) – Commonsense reasoning dataset.

## Learning Resources

- [HELM Overview](https://crfm.stanford.edu/helm/latest/) – Intro to full-spectrum model benchmarking.
- [LLM Evaluation Guide (HuggingFace)](https://huggingface.co/docs/transformers/main/en/evaluation) – End-to-end guide for evaluating language models.
- [Stanford CS25 Notes](https://web.stanford.edu/class/cs25/) – Covers benchmarking and model evaluation basics.
- [MLPerf](https://mlcommons.org/en/training-normal/) – Industry-standard ML performance benchmarking guidelines.
- [DeepMind Papers on Evaluation](https://deepmind.google/research) – Research on model testing and evaluation.

## Related Awesome Lists

- [Awesome AI](https://github.com/awesomelistsio/awesome-ai)
- [Awesome AI Safety & Alignment](https://github.com/awesomelistsio/awesome-ai-safety-alignment)
- [Awesome AI Security](https://github.com/awesomelistsio/awesome-ai-security)
- [Awesome AI Research Tools](https://github.com/awesomelistsio/awesome-ai-research-tools)
- [Awesome Machine Learning](https://github.com/awesomelistsio/awesome-machine-learning)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
