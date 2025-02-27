# SEA-LION V3 9B



Our SEA-LIONv3 Gemma2-9B base model has been continued pre-trained on top of the Gemma2 base model that is 9 billion parameters in size, and has a context length of 8192.

The training data for SEA-LIONv3 Gemma2-9B comprises 200 billion tokens of Burmese, Chinese, English, Filipino, Indonesia, Khmer, Lao, Malay, Tamil, Thai and Vietnamese. The training data is sampled from the Dolma dataset, the original SEA-LION pretraining data, and Wiki sources for Burmese, Chinese, English, Filipino, Khmer, Lao, Malay, Indonesian, Tamil, Thai and Vietnamese. In addition, the training data for SFT includes Javanese and Sudanese.

The hardware used for continued pre-training SEA-LIONv3 Gemma2-9B comprises 64 Nvidia H100 GPUs on the Singtel’s AI Cloud infrastructure. The training duration was 10 days for the SEA-LIONv3 Gemma2-9B base model.

SEA-LIONv3 Gemma2-9B benefits from the strong Gemma2 performance in Southeast Asian (SEA) languages, allowing it to significantly outperform its predecessors across SEA evaluation metrics, indicating improved language capabilities for the SEA region.

Due to its pre-training and fine-tuning data mix, SEA-LIONv3 Gemma2-9B exhibits a boost in natural language reasoning (NLR) abilities in Indonesian, Tamil, Thai and Vietnamese, and achieves state-of-the-art performances in SEA instruction-following and multi-turn chat, while retaining Gemma2’s general abilities.


## Gemma2 9B CPT SEA-LIONv3 Base
### Training Infrastructure
### Tokenizer
### Training Data
### Benchmark Performance

## Gemma2 9B CPT SEA-LIONv3 Base Instruct
### Fine-Tuning Methodology
### Fine-Tuning Data
### Benchmark Performance

## Gemma2 9B CPT SEA-LIONv3 Base Instruct GGUF

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

