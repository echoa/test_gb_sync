# SEA-LION (South East Asian Languages In One Network)

_Built for Southeast Asia, by Southeast Asia_

South East Asian Languages in One Network (SEA-LION) is a family of open-source Large Language Models (LLMs) that better understands Southeast Asia’s (SEA) diverse contexts, languages, and cultures.

It is an open-source project anchored by the Products Pillar of AI Singapore. Our work in SEA-LION aims to create LLMs that cater to under-represented population groups and low resource languages in the SEA region.

This guide provides information and resources on SEA-LION including how to access the models, hosting, and how-to guides.

You can refer to here to read more about our motivations for SEA-LION, please 

| Model Version | Release Date | Key Features |
|---------------|--------------|--------------|
| v1            | January 2022 | Outperformed most models based on SEA-HELM |
| v2            | June 2022    | Improved performance on SEA tasks and standard benchmarks |
| v2.1          | December 2022| Enhanced conversational abilities in SEA languages |
| v3            | July 2023    | Outperforms similar sized open source models and some larger models |
Latest Models: 


# What is SEA-LION



## Transparent and Open Source
We have benefited greatly from the open-source community and believe that efforts to better represent our region will similarly be well served by open-source efforts. SEA-LION will therefore be open and transparent in the following areas throughout this guide:

1. Pre-Training data SEA-LION-PILE
2. Model training code
3. Model weights
4. Fine-Tuning data
5. Evaluation benchmarks GitHub

# Why SEA-LION

Large Language Models (LLMs) are a type of artificial intelligence model designed to understand and generate human language. They are trained on vast amounts of text data and can perform a wide range of tasks such as translation, summarization, answering questions, and even writing code.

Existing LLMs display strong bias in terms of cultural values, political beliefs and social attitudes. This is due to the training data, especially those scraped from the Internet, which often has disproportionately large influences from western, industrialized, rich, educated, and democratic (WIRED) societies. People from non-WIRED societies are less likely to be literate, to use the Internet, and to have their output easily accessed.

Our work in SEA-LION, now part of Singapore’s National Multi-Modal Large Language Model project, aims to create LLMs that cater to under-represented population groups and low resource languages in the SEA region.

SEA-LION is trained on more content produced in Southeast Asian languages like Thai, Vietnamese and Bahasa Indonesia to ensure better representation in data and alignment compared to Western or Chinese models. SEA-LION models understand nuances in SEA languages and demonstrate greater awareness of cultural context specific to the region. This lowers the bar for adoption by governments, enterprises, and academia, while effectively expanding the Southeast Asian languages and cultural representation in the mainstream LLMs which are currently dominated by models predominantly trained on a corpus of English data from the western, developed world.

SEA-LION has seen:

- In v1, ability to outperform most models based on SEA-HELM when it was released
- In v2, outperformance for SEA tasks, while retaining credible performance on standard (English) benchmarks
- In v2.1, key improvements in conversational abilities across SEA languages, while providing more helpful and contextually appropriate responses to user prompts
- In v3, outperforms similar sized open source models, and even some larger models in both general and SEA capabilities
*SEA-HELM: SouthEast Asian Holistic Evaluation of Language Models

Visit our Leaderboard for more information on:
1. How SEA-LION compares to other available models along different metrics
2. What SEA-HELM is and the four key capabilities it is evaluated on: English performance, Proficiency in SEA chat, Instruction-following and Linguistic tasks
3. What each of these globally recognized metrics mean under SEA-HELM


## Key Features of SEA-LION

<table>
  <thead>
    <tr>
      <th>Model Collection</th>
      <th>Size</th>
      <th>Context Length</th>
      <th>Training Strategy</th>
      <th>Available in</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">SEA-LION v3</td>
      <td>9B</td>
      <td>8192</td>
      <td>CPT<sup>1</sup> of Gemma2</td>
      <td>Base, Instruct, GGUF</td>
    </tr>
    <tr>
      <td>8B</td>
      <td>128K</td>
      <td>CPT of Llama 3.1 8B</td>
      <td>Base, Instruct, GGUF</td>
    </tr>
    <tr>
      <td>70B</td>
      <td>128K</td>
      <td>CPT of Llama 3.1 70B</td>
      <td>Base, Instruct, GGUF</td>
    </tr>
    <tr>
      <td>SEA-LION v2</td>
      <td>8B</td>
      <td>8192</td>
      <td>CPT of Llama3</td>
      <td>Base, Instruct, GGUF</td>
    </tr>
    <tr>
      <td rowspan="2">SEA-LION v1</td>
      <td>3B</td>
      <td>2048</td>
      <td>Pre-training from scratch</td>
      <td>Base</td>
    </tr>
    <tr>
      <td>7B</td>
      <td>2048</td>
      <td>Pre-training from scratch</td>
      <td>Instruct</td>
    </tr>
  </tbody>
</table>

<h6><sup>1</sup> Continued Pre-Training<h6>