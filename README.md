# MSc. Human-Centered Artificial Intelligence, DTU Compute anno 2025

This repository collects papers and resources related to applying the SAE interpretability idea to the Life2Vec model, scrutinizing its inner workings and assessing whether they are indeed interpretable.

---

## Primary Papers

The table below tracks your primary reading list. For each paper, you can mark whether you have finished reading or are currently reading it, add a brief description of its key points, and provide a clickable title with the publication date in parentheses.

| Status       | Paper Title (Year)                                                                                                                                                                      | Description                                     | Link                                                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| ✔️ | **Anthropic: Towards Monosemanticity (2023)**                                                                                                                                           | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2023/monosemantic-features)                                           |
| ✔️ | **Anthropic: Scaling Monosemanticity (2024 follow-up)**                                                                                                                                 | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/scaling-monosemanticity/)                                         |
| ✔️ | **Life2Vec (Nature): Using sequences of life-events to predict human lives (2023)** <br> *First read-through (65%)*                                                                    | *(Key points summary…)*                         | [Link](https://www.nature.com/articles/s43588-023-00573-5)                                                     |
| ❎  | **BERT – Bidirectional Encoder Representation of Transformers (Google, 2018)**                                                                                                          | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/1810.04805)                                                                       |

---

## Resources

This section includes additional readings and materials related to Mechanistic Interpretability using Sparse Autoencoders on LLMs/Transformers. The checklist helps you track progress—use `[x]` for finished readings and `[ ]` for those in progress (📖 indicates “currently reading”). Feel free to add a brief description to capture the primary insights from each resource.

| Status       | Resource Title (Year/Info)                                                                                                                                                              | Description                                     | Link                                                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| ❎  | **Anthropic: Update on SAE training regime (2024)**                                                                                                                                   | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/april-update/index.html#training-saes)                            |
| ✔️ | **Anthropic: Toy Models of Superposition (2022)**                                                                                                                                       | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2022/toy_model/index.html)                                             |
| ❎  | **Sparse Crosscoders for Cross-Layer Features and Model Diffing (2024)**                                                                                                                | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/crosscoders/index.html)                                           |
| ✔️ | **Chris Olah – Dark Matter of AI – MechInterp (2024)**                                                                                                                                  | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/july-update/index.html#dark-matter)                               |
| ❎  | **Privileged Bases in Transformer Residual Stream (2023)**                                                                                                                              | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2023/privileged-basis/index.html)                                      |
| ✔️ | **Chris Olah – Zoom In: An Introduction to Circuits (2020)**                                                                                                                            | *(Key points summary…)*                         | [Link](https://distill.pub/2020/circuits/zoom-in/)                                                             |
| ✔️ | **A Mathematical Framework for Transformer Circuits (2021)**                                                                                                                            | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2021/framework/index.html)                                             |
| ❎  | **The Geometry of Concepts: Sparse Autoencoder Feature Structure (2024)**                                                                                                                | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2410.19750)                                                                       |
| ❎  | **Scaling and Evaluating SAE's (2024)**                                                                                                                                                 | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2406.04093)                                                                       |
| ❎  | **Neel Nanda – MechInterp (SAE) podcast (2024)** <br> 📖                                                                                                                               | *(Key points summary…)*                         | [Link](https://podcasts.apple.com/dk/podcast/neel-nanda-mechanistic-interpretability-sparse-autoencoders/id1510472996?i=1000679600572) |
| ❎  | **DeepMind – Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2 (2024)**                                                                                              | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2408.05147)                                                                       |
| ❎  | **Trading off performance and human oversight in algorithmic policy: evidence from Danish college admissions (2024, Magnus)**                                                              | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2411.15348)                                                                       |
| ❎  | **SAE's find highly interpretable features in LLM's (2023)**                                                                                                                            | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2309.08600)                                                                       |
| ❎  | **(BERT?) Transformer visualization via dictionary learning: contextualized embedding as linear superposition of transformer factors (2023)**                                           | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2103.15949)                                                                       |
| ❎  | **Codebook features: Sparse and Discrete interpretability for neural networks (2023)**                                                                                                   | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2310.17230)                                                                       |
| ✔️ | **YouTube: 3Blue1Brown – Visual explanation of LLM and Transformers (series)**                                                                                                          | *(Key points summary…)*                         | [Link](https://www.youtube.com/watch?v=wjZofJX0v4M)                                                            |
| ✔️ | **YouTube: Welch Labs – Dark matter of AI**                                                                                                                                             | *(Key points summary…)*                         | [Link](https://www.youtube.com/watch?v=UGO_Ehywuxc)                                                             |
| ❎  | **OpenAI: LLM can explain neurons in LLM (2023)**                                                                                                                                       | *(Key points summary…)*                         | [Link](https://openaipublic.blob.core.windows.net/neuron-explainer/paper/index.html)                            |
| ❎  | **Word2Vec – Efficient Estimation of Word Representation in Vector Space (2013)**                                                                                                         | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/1301.3781)                                                                        |
| ❎  | **DeepMind – Improving Dictionary Learning with Gated SAE's (2024)**                                                                                                                     | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2404.16014)                                                                       |
| ❎  | **Improving SAE's by SQRT-L1 and Removing lowest activating features (article, 2024)**                                                                                                    | *(Key points summary…)*                         | [Link](https://www.lesswrong.com/posts/YiGs8qJ8aNBgwt2YN/improving-sae-s-by-sqrt-ing-l1-and-removing-lowest)     |
| ❎  | **Scratchpads: Show your work – Intermediate computation with LLM's (used in Anthropic) (2021)**                                                                                         | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2112.00114)                                                                       |
| ❎  | **Neel Nhanda – An opinionated list of favourite papers v2 (2024)** <br> 📖                                                                                                             | *(Key points summary…)*                         | [Link](https://www.alignmentforum.org/posts/NfFST5Mio7BCAQHPA/an-extremely-opinionated-annotated-list-of-my-favourite) |
| ❎  | **GitHub with MechInterp in LLM's – Code and paper references**                                                                                                                         | *(Key points summary…)*                         | [Link](https://github.com/ruizheliUOA/Awesome-Interpretability-in-Large-Language-Models)                         |
| ✔️ | **Decoding the Thought Vector (early work on sparsity) (2016)**                                                                                                                         | *(Key points summary…)*                         | [Link](https://gabgoh.github.io/ThoughtVectors/)                                                               |
| ❎  | **Multimodal neurons in ANN (fires regardless of modality) (2021)**                                                                                                                     | *(Key points summary…)*                         | [Link](https://distill.pub/2021/multimodal-neurons/)                                                          |
| ✔️ | **Comments and counter-points to Anthropic's paper**                                                                                                                                    | *(Key points summary…)*                         | [Link](https://www.lesswrong.com/posts/zzmhsKx5dBpChKhry/comments-on-anthropic-s-scaling-monosemanticity)       |
| ✔️ | **Interpretability Illusion for BERT (2021)** <br> *(First idea of dataset-level neuron levels; noted superposition effects)*                                                          | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2104.07143)                                                                       |
| ✔️  | *(Return to this, original SAE idea?!) **[Interim research report] Taking features out of superposition with sparse autoencoders (2022)**                                                                                        | *(Key points summary…)*                         | [Link](https://www.lesswrong.com/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition) |
| ❎  | **Grammar of Life – Large Language Models Share Representations of Latent Grammatical Concepts Across Typologically Diverse Languages (2025)**                                          | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2501.06346)                                                                       |

---

## Additional Buzzwords, Open Questions, and Explorations

- *k*-top SAE, Gated SAE, JumpReLU (w.r.t. the expensiveness of training SAE's; possibly also yielding better performance — per Neel’s suggestions)
- GeLU vs. ReLU: Which activation function works best in practice?
- Measuring SAE performance: What are the most effective evaluation metrics?
- Investigate potential periodicity in Life2Vec embedding maps (e.g., via t-SNE) and any inherent structure.
- Explore causality and model introspection in Life2Vec, especially in relation to SAE usage.
- Understand Byte-paired tokenization: Find relevant papers and assess its impact.
- If Life2Vec employs BERT, explore the underlying paper for deeper insights.
- Delve into transformer circuits: How can QK and OV be “decomposed” and “disentangled”?
- **Open Question:** Does Life2Vec include an MLP? If not, how and where are the neuron activations obtained?

---

## SAE Resources

- [GitHub of SAE training code](https://github.com/ai-safety-foundation/sparse_autoencoder)
- [ARENA course and exercises (recommended by Neel)](https://arena-chapter0-fundamentals.streamlit.app/)
