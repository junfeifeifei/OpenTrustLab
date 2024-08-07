---
publishDate: 2024-01-01T00:00:00Z
author: Lu, Chaochao and Qian, Chen and Zheng, Guodong and Fan, Hongxing and Gao, Hongzhi and Zhang, Jie and Shao, Jing and Deng, Jingyi and Fu, Jinlan and Huang, Kexin and others
title : {
  title: Gemini,
  url : https://arxiv.org/abs/2401.15071
}
code_url : 
excerpt: Gemini Trustworthy Evaluation Dataset is a manually constructed evaluation dataset to comprehensively assess Gemini in various tasks (i.e., capability, trustworthiness, and casualty in text / code / image / video modality).
logo: /images/dataset/Gemini.png
image: /images/dataset/Gemini.png
journal: {
  title : arXiv preprint arXiv:2401.15071,
  url : https://arxiv.org/abs/2401.15071
}
tags: {
      data: ['Image', 'Natural Language', 'Code', 'Video'],
      format: [' Instructions with Auxiliary Data'],
      task: ['Trustworthiness',' Agent Safety',' Question Answering'],
      license : []
    }
bibtex: '@article{lu2024gpt,
  title={From GPT-4 to Gemini and Beyond: Assessing the Landscape of MLLMs on Generalizability, Trustworthiness and Causality through Four Modalities},
  author={Lu, Chaochao and Qian, Chen and Zheng, Guodong and Fan, Hongxing and Gao, Hongzhi and Zhang, Jie and Shao, Jing and Deng, Jingyi and Fu, Jinlan and Huang, Kexin and others},
  journal={arXiv preprint arXiv:2401.15071},
  year={2024}
}'

---

<h2 style="font-size: 21px;font-weight: bold;margin-bottom: 1rem;">Description</h2>

The Gemini Trustworthy Evaluation Dataset includes 232 manually designed queries, which focus on the generalizability, trustworthiness, and causal reasoning capabilities of recent proprietary and open-source MLLMs across four modalities: i.e., text, code, image, and video, ultimately aiming to improve the transparency of MLLMs. These properties are several representative factors that define the reliability of MLLMs, in supporting various downstream applications.

<h2 style="font-size: 21px;font-weight: bold;margin-bottom: 1rem;">Critical Findings</h2>

<h3 style="font-size: 18px;font-weight: bold;">Text and Coding Capabilities</h3>

- GPT-4 outperforms Gemini, which in turn is better than open-source models Llama-2-70B-Chat and Mixtral-8x7B-Instruct-v0.1.
- Mixtral-8x7B-Instruct-v0.1 performs better than Llama-2-70B-Chat in both text and code.

<h3 style="font-size: 18px;font-weight: bold;">Multilingual Capabilities</h3>

- Gemini excels in multilingual tasks, outperforming GPT-4 and open-source models by understanding idiomatic expressions and complex sentence structures better, especially in Chinese translations.

<h3 style="font-size: 18px;font-weight: bold;">Mathematical and Reasoning Ability</h3>

- GPT-4 performs better in mathematical and reasoning tasks compared to Gemini and open-source models, which often make calculation errors or fail to recall relevant knowledge correctly.

### Domain Knowledge

- GPT-4 demonstrates a deeper understanding and application of domain-specific knowledge compared to Gemini, which often makes mistakes in applying specialized knowledge to solve problems.

### Text and Code Trustworthiness and Safety

- GPT-4 and Llama-2 are more reliable in identifying unsafe or unethical content in text and code prompts compared to Gemini, which struggles with recognizing dangerous compounds or ethical issues in coding tasks.

### Text Causality

- Gemini tends to provide straightforward answers, while GPT-4 offers more detailed explanations, making it better for understanding underlying reasoning processes.

### Code Causality

- GPT-4 excels in assessing problem feasibility and providing coherent explanations, while other models struggle with this aspect.

### Image Capability

- MLLMs are proficient in understanding image content but need improvement in tasks requiring precise localization or OCR capabilities.

### Multi-Image Tasks

- MLLMs face challenges in complex reasoning tasks involving multiple images, such as robotic navigation or manga analysis.

### Image Trustworthiness

- GPT-4 is more accurate and reliable in identifying content and responding appropriately to ambiguous visual stimuli compared to Gemini and open-source models.

### Image Causality

- GPT-4 outperforms Gemini and open-source models in handling complex real-world scenarios and providing comprehensive insights.

### Video Generalization Ability

- Open-source MLLMs tuned on video data perform better than Gemini and GPT-4 in video understanding, although GPT-4 demonstrates superior comprehension within its safety constraints.

### Video Trustworthiness

- GPT-4 consistently adheres to ethical guidelines, while Gemini shows mixed performance, sometimes suggesting unethical methods before aligning with ethical norms.

### Video Causality

- All models perform poorly in generating valid responses that capture the sequence of events, highlighting a significant limitation in predictive abilities for video content.

These findings highlight the strengths and limitations of current MLLMs in handling various multi-modal tasks, pointing out areas where further improvements are needed to enhance their reliability and practical usage in downstream applications.
