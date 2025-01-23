# SEA-LION (South East Asian Languages in One Network)

_Built for Southeast Asia, by Southeast Asia_

South East Asian Languages in One Network (SEA-LION) is a family of open-source Large Language Models (LLMs) that better understands Southeast Asia’s (SEA) diverse contexts, languages, and cultures.

It is an open-source project anchored by the Products Pillar of AI Singapore. Our work in SEA-LION aims to create LLMs that cater to under-represented population groups and low resource languages in the SEA region. You can [read more about our motivations for SEA-LION here](overview/why_sealion.md).

This guide provides information and resources on SEA-LION including how to access the models, hosting, and how-to guides.

## Key Features of SEA-LION

<table><thead><tr><th width="171">Model Collection</th><th width="73">Size</th><th width="151">Context Length</th><th width="234">Training Strategy</th><th>Available in</th></tr></thead><tbody><tr><td>SEA-LION v3</td><td>9B</td><td>8192</td><td>CPT1 of Gemma2</td><td>Base, Instruct, GGUF</td></tr><tr><td></td><td>8B</td><td>128K</td><td>CPT of Llama 3.1 8B</td><td>Base, Instruct, GGUF</td></tr><tr><td></td><td>70B</td><td>128K</td><td>CPT of Llama 3.1 70B</td><td>Base, Instruct, GGUF</td></tr><tr><td>SEA-LION v2</td><td>8B</td><td>8192</td><td>CPT of Llama3</td><td>Base, Instruct, GGUF</td></tr><tr><td>SEA-LION v1</td><td>3B</td><td>2048</td><td>Pre-training from scratch</td><td>Base</td></tr><tr><td></td><td>7B</td><td>2048</td><td>Pre-training from scratch</td><td>Instruct</td></tr></tbody></table>

**1 Continued Pre-Training**

\


## Performance and Benchmarks

SEA-LION has seen:

* In v1, ability to outperform most models based on SEA-HELM (SouthEast Asian Holistic Evaluation of Language Models) when it was released
* In v2, outperformance for SEA tasks, while retaining credible performance on standard (English) benchmarks
* In v2.1, key improvements in conversational abilities across SEA languages, while providing more helpful and contextually appropriate responses to user prompts
* In v3, outperforms similar sized open source models, and even some larger models in both general and SEA capabilities

We use a holistic approach to evaluation, including not just traditional Natural Language Processing (NLP) benchmarking tasks (such as sentiment analysis and question answering) but also [meticulously handcrafted linguistic and cultural diagnostic tests tailored to Southeast Asia](https://arxiv.org/abs/2309.06085v2).

Visit our [Leaderboard](https://leaderboard.sea-lion.ai/) for more detailed breakdown on:

1. How SEA-LION compares to other available models along different metrics
2. What SEA-HELM is and the four key capabilities it is evaluated on: English performance, Proficiency in SEA chat, Instruction-following and Linguistic tasks
3. What each of these globally recognized metrics mean under SEA-HELM

## Licensing

**Transparent and Open Source**

We have benefited greatly from the open-source community and believe that efforts to better represent our region will similarly be well served by open-source efforts.

All SEA-LION releases will therefore embrace an open-source ethos under the MIT license as much as possible; however, the exact licensing terms may vary depending on the underlying base model’s restrictions or requirements. For instance, if the model leverages Meta’s Llama3 codebase, it may be bound by the [Llama3 License](https://huggingface.co/meta-llama/Meta-Llama-3-8B/blob/main/LICENSE), which places certain restrictions on commercial use. Similarly, the Gemma2-based variants may carry different terms. Users should always refer to the Hugging Face model card of each specific SEA-LION model for the most accurate, up-to-date license information.

SEA-LION will also be open and transparent in the following areas throughout this guide:

1. Pre-Training data
2. Model training code
3. Fine-Tuning data
4. Evaluation benchmarks

## Community

We welcome contributions to SEA-LION! Check out the [contributing guide](overview/contributing.md) to get started.

Some ways to contribute:

* Report bugs and issues
* Enhance the documentation
* Add more model evaluation tasks and metrics
* Train versions of the model in more SEA languages

Check out our [collaborations guide](overview/collaboration.md) also, for possible ways to further enhance and expand the capabilities of SEA-LION together.

## To Cite SEA-LION

If you use SEA-LION in your work, please cite it as:

```bibtex
@misc{sea_lion_2024,
  title={SEA-LION (Southeast Asian Languages In One Network): A Family of Large Language Models for Southeast Asia},
  author={AI Singapore},
  year={2024},
  howpublished={\url{https://github.com/aisingapore/sealion}}
}
```

## Acknowledgements

AI Singapore is a national programme supported by the National Research Foundation, Singapore and hosted by the National University of Singapore. Any opinion, finding, conclusion or recommendation expressed in this material are those of the author(s) and do not reflect the views of National Research Foundation, Singapore, or the National University of Singapore.

We also grateful for the support of the Infocomm Media Development Authority (IMDA) of Singapore.

SEA-LION would not be possible without a growing list of Singapore, regional, and international collaborators. Please see our website for more details.

## Contact

If you have questions, comments, or issues, please open a GitHub issue or contact us via this [SEA-LION Inquiry Form](https://forms.gle/sLCUVb95wmGf43hi6).
