# SEA-LION V3 70B
## Introduction
Our SEA-LIONv3 Llama3.1 8B and 70B base models have been continued pre-trained on top of the Llama3.1 8B and 70B models respectively. Both have a context length of 128K, making them the SEA-LION models with the longest context length to date.

Both models were continued pre-trained with 200 billion tokens of SEA data from languages such as Thai, Vietnamese, Tamil, and Indonesian, sourced from diverse datasets, including Wiki and Dolma. The fine-tuning process involved 9.5 million English instructions for math and reasoning (Stage 1) and 7.3 million multilingual prompts, emphasising SEA languages and tasks (Stage 2).

Training utilised Nvidia H100 and H200 GPUs on AWS and SingTel AI Cloud, with training durations of approximately 136 hours for the 8B variant and 495 hours for the 70B variant. Both models employ bfloat16 precision and advanced optimisation techniques like decoupled_adamw.

SEA-LION v3 supports 13 SEA languages – 11 SEA languages (Burmese, Chinese, English, Filipino, Indonesia, Khmer, Lao, Malay, Tamil, Thai and Vietnamese) are included in the pre-training data, and 2 more additional SEA languages (Javanese and Sundanese) are included in the SFT data – and demonstrates strong cross-lingual capabilities. It achieves state-of-the-art performance on regional benchmarks like SEA-HELM and outperforms models such as Llama 3.3 70B Instruct on key metrics.

With enhanced natural language reasoning (NLR) abilities and superior instruction-following in SEA languages, SEA-LION v3 sets new standards in multilingual AI for the region.

At a glance:
- **Model type:** Decoder
- **Tokenizer**: Default tokenizer used in Llama 3 8B Instruct
- **Available Formats**:
  - Base (llama3-8b-cpt-sea-lionv2-base)
  - Instruct (llama3-8b-cpt-sea-lionv2.1-instruct)
  - GGUF (llama3-8b-cpt-sea-lionv2.1-instruct-gguf)
- **Languages supported:** English, Indonesian, Thai, Vietnamese, Tamil
- **License:**  [Llama3.1 Community License](https://github.com/meta-llama/llama-models/blob/main/models/llama3_1/LICENSE


## LLAMA3.1 70B CPT SEA-LIONv3.1 Base
### Training Infrastructure
### Tokenizer
### Training Data
### Benchmark Performance

## LLAMA3.1 70B CPT SEA-LIONv3.1 Instruct
### Fine-Tuning Methodology
### Fine-Tuning Data
### Benchmark Performance

## LLAMA3.1 70B CPT SEA-LIONv3.1 Instruct GGUF

## Download the Model

## Usage 

## Disclaimer

It is important for users to be aware that our models exhibits certain limitations that warrant consideration:
1. The model can hallucinate and occasionally generates irrelevant content, introducing fictional elements that are not grounded in the provided context. Users should also exercise caution in interpreting and validating the model's responses due to the potential inconsistencies in its reasoning. 
2. The model has not been aligned for safety. Developers and users should perform their own safety fine-tuning and related security measures. In no event shall the authors be held liable for any claims, damages, or other liabilities arising from the use of the released weights and codes.

<br>

## References
### Thai Pre-Training Data Reference

```bibtex
@misc{lowphansirikul2021wangchanberta,
    title={WangchanBERTa: Pretraining transformer-based Thai Language Models},
    author={Lalita Lowphansirikul and Charin Polpanumas and Nawat Jantrakulchai and Sarana Nutanong},
    year={2021},
    eprint={2101.09635},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
