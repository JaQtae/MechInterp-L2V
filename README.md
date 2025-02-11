# MSc. Human-Centered Artificial Intelligence, DTU Compute anno 2025

This repository collects papers and resources related to applying the SAE interpretability idea to the Life2Vec model, scrutinizing its inner workings and assessing whether they are indeed interpretable.

---

## Primary Papers

The following papers are the primary ones contributing to the thesis and its foundational principles:

| Status       | Paper Title (Year)                                                                                                                                                                      | Description                                     | Link                                                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| ✔️ | **Anthropic: Towards Monosemanticity (2023)**                                                                                                                                           | *Uses L1 and L2 loss to promote sparsity in SAE. Good plots. Some critiques? Parallel to Cunningham et al., based on [this](https://www.lesswrong.com/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition) partially. (More notes required)*                         | [Link](https://transformer-circuits.pub/2023/monosemantic-features)                                           |
| ✔️ | **Anthropic: Scaling Monosemanticity (2024 follow-up)**                                                                                                                                 | *Follow-up of above, focusing on the scaling of SAE's to the larger LLM's.*                         | [Link](https://transformer-circuits.pub/2024/scaling-monosemanticity/)                                         |
| ✔️ | **Life2Vec (Nature): Using sequences of life-events to predict human lives (2023)** <br> *First read-through (65%)*                                                                    | *Represents life-events as a sequence and trains on registry data using a BERT model. More models exist now (HGMAE, GPT-like soon™️), SOTA baseline.*                         | [Link](https://www.nature.com/articles/s43588-023-00573-5)                                                     |
| 📖  | **BERT – Bidirectional Encoder Representation of Transformers (Google, 2018)**                                                                                                          | *Contextualizes attention bidirectionally through masking. Transformer structure.*                         | [Link](https://arxiv.org/pdf/1810.04805)                                                                       |

---

## Resources

Materials related to Mechanistic Interpretability using Sparse Autoencoders on LLMs/Transformers. The checklist helps keeping track of progress  (📖 indicates “currently reading”). A brief description to capture the primary insights from each resource is available.

| Status       | Resource Title (Year/Info)                                                                                                                                                              | Description                                     | Link                                                                                                         |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| ❎  | **Anthropic: Update on SAE training regime (2024)**                                                                                                                                   | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/april-update/index.html#training-saes)                            |
| ✔️ | **Anthropic: Toy Models of Superposition (2022)**                                                                                                                                       | *Investigates superposition principle in Transformers using small toy models. Very informative w.r.t. bases and relates back to several papers below.*                         | [Link](https://transformer-circuits.pub/2022/toy_model/index.html)                                             |
| ❎  | **Sparse Crosscoders for Cross-Layer Features and Model Diffing (2024)**                                                                                                                | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/crosscoders/index.html)                                           |
| ✔️ | **Chris Olah – Dark Matter of AI – MechInterp (2024)**                                                                                                                                  | *(Key points summary…)*                         | [Link](https://transformer-circuits.pub/2024/july-update/index.html#dark-matter)                               |
| ✔️  | **Privileged Bases in Transformer Residual Stream (2023)**                                                                                                                              | *Identifies ADAM as possible culprit of privileged bases - they observe heavy-tailed activations inside the computation basis, but not in the residual stream.*                         | [Link](https://transformer-circuits.pub/2023/privileged-basis/index.html)                                      |
| ✔️ | **Chris Olah – Zoom In: An Introduction to Circuits (2020)**                                                                                                                            | *First notion of circuits. Visual explanation based on InceptionV1 (iirc), good grokking paper.*                         | [Link](https://distill.pub/2020/circuits/zoom-in/)                                                             |
| ✔️ | **A Mathematical Framework for Transformer Circuits (2021)**                                                                                                                            | *Foundational paper describing a Transformer as a circuit (QK, OV) and a mathematical way of understanding said circuits. Good entry for understanding foundational principles.*                         | [Link](https://transformer-circuits.pub/2021/framework/index.html)                                             |
| ❎  | **The Geometry of Concepts: Sparse Autoencoder Feature Structure (2024)**                                                                                                                | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2410.19750)                                                                       |
| ❎  | **Scaling and Evaluating SAE's (2024)**                                                                                                                                                 | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2406.04093)                                                                       |
| 📖  | **Neel Nanda – MechInterp (SAE) podcast (2024)**                                                                                                                                 | *General rant about open problems and interesting avenues/ways to think about mechanistic interpretability in a fast and growing field of research.*                         | [Link](https://podcasts.apple.com/dk/podcast/neel-nanda-mechanistic-interpretability-sparse-autoencoders/id1510472996?i=1000679600572) |
| ❎  | **DeepMind – Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2 (2024)**                                                                                              | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2408.05147)                                                                       |
| ❎  | **Trading off performance and human oversight in algorithmic policy: evidence from Danish college admissions (2024, Magnus)**                                                              | *(Key points summary…)*                         | [Link](https://arxiv.org/abs/2411.15348)                                                                       |
| ✔️  | **SAE's find highly interpretable features in LLM's (2023)**                                                                                                                            | *Uses autointerpretability (Bills et al.) with an SAE to intervene on activations layers in Pythia model. Comparison baselines are (1) default (2) random directions (3) PCA (4) ICA. Later layers less interpretable? Uses activation patching and ACDC for causality checks.*                         | [Link](https://arxiv.org/pdf/2309.08600)                                                                       |
| ❎  | **(BERT?) Transformer visualization via dictionary learning: contextualized embedding as linear superposition of transformer factors (2023)**                                           | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2103.15949)                                                                       |
| ❎  | **Codebook features: Sparse and Discrete interpretability for neural networks (2023)**                                                                                                   | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2310.17230)                                                                       |
| ✔️ | **YouTube: 3Blue1Brown – Visual explanation of LLM and Transformers (series)**                                                                                                          | *(Key points summary…)*                         | [Link](https://www.youtube.com/watch?v=wjZofJX0v4M)                                                            |
| ✔️ | **YouTube: Welch Labs – Dark matter of AI**                                                                                                                                             | *(Key points summary…)*                         | [Link](https://www.youtube.com/watch?v=UGO_Ehywuxc)                                                             |
| ❎  | **OpenAI: LLM can explain neurons in LLM (2023)**                                                                                                                                       | *(Key points summary…)*                         | [Link](https://openaipublic.blob.core.windows.net/neuron-explainer/paper/index.html)                            |
| 📖  | **Word2Vec – Efficient Estimation of Word Representation in Vector Space (2013)**                                                                                                         | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/1301.3781)                                                                        |
| ❎  | **DeepMind – Improving Dictionary Learning with Gated SAE's (2024)**                                                                                                                     | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2404.16014)                                                                       |
| ❎  | **Improving SAE's by SQRT-L1 and Removing lowest activating features (article, 2024)**                                                                                                    | *(Key points summary…)*                         | [Link](https://www.lesswrong.com/posts/YiGs8qJ8aNBgwt2YN/improving-sae-s-by-sqrt-ing-l1-and-removing-lowest)     |
| ❎  | **Scratchpads: Show your work – Intermediate computation with LLM's (used in Anthropic) (2021)**                                                                                         | *(Key points summary…)*                         | [Link](https://arxiv.org/pdf/2112.00114)                                                                       |
| 📖  | **Neel Nhanda – An opinionated list of favourite papers v2 (2024)**                                                                                                             | *Contains primary papers for new people in the field and highlights important sections or ideas of each paper to focus on.*                         | [Link](https://www.alignmentforum.org/posts/NfFST5Mio7BCAQHPA/an-extremely-opinionated-annotated-list-of-my-favourite) |
| ❎  | **GitHub with MechInterp in LLM's – Code and paper references**                                                                                                                         | *A general repo I found.*                         | [Link](https://github.com/ruizheliUOA/Awesome-Interpretability-in-Large-Language-Models)                         |
| ✔️ | **Decoding the Thought Vector (early work on sparsity) (2016)**                                                                                                                         | *Early work on sparsity and to some extent superposition (iirc). Primarily through the lens of visual model.*                         | [Link](https://gabgoh.github.io/ThoughtVectors/)                                                               |
| ❎  | **Multimodal neurons in ANN (fires regardless of modality) (2021)**                                                                                                                     | *Despite modality a concept can be recognized in neuron activations.*                         | [Link](https://distill.pub/2021/multimodal-neurons/)                                                          |
| ✔️ | **Comments and counter-points to Anthropic's paper**                                                                                                                                    | *(Key points summary…)*                         | [Link](https://www.lesswrong.com/posts/zzmhsKx5dBpChKhry/comments-on-anthropic-s-scaling-monosemanticity)       |
| ✔️ | **Interpretability Illusion for BERT (2021)**                                                          | *(First idea of dataset-level neuron levels; noted superposition effects)*                         | [Link](https://arxiv.org/pdf/2104.07143)                                                                       |
| ✔️  | *(Return to this, original SAE idea?!)* **[Interim research report] Taking features out of superposition with sparse autoencoders (2022)**                                                                                        | *Highlights some challenges in terms of disentangling the complex neuron representations from the SAE. Uses MMCS, finds Goldilocks zone for L1 and dictionary size, important to track dead neurons and loss "stickiness" to identify optimal hyperparameters. (see Anthropic for more nuance?)*                         | [Link](https://www.lesswrong.com/posts/z6QQJbtpkEAX3Aojj/interim-research-report-taking-features-out-of-superposition) |
| 📖  | **Grammar of Life – Large Language Models Share Representations of Latent Grammatical Concepts Across Typologically Diverse Languages (2025)**                                          | *Features capture generalizable abstractions in language. Uses Gated SAEs to reduce bias from L1 term (unlike Anthropic), which "separates <ins> selecting features to use </ins> and <ins> estimating activation magnitude of those directions </ins>".*                         | [Link](https://arxiv.org/pdf/2501.06346)                                                                       |

---

## Additional Buzzwords, Open Questions, and Explorations

- *k*-top SAE, Gated SAE, JumpReLU (w.r.t. the expensiveness of training SAE's; possibly also yielding better performance — per Neel’s suggestions Gated is the way to go)
  - Gated SAE's are better than what Anthropic did, because they avoid the bias introduced from L1 w.r.t. harming L2. (Rajamanoharan et al. (2024)) 
- GeLU vs. ReLU: Which activation function works best in practice? (Neel says GeLU...)
- Measuring SAE performance: What are the most effective evaluation metrics? (Huben email sources, his input is to focus on how you can evaluate the features)
- Understand Byte-paired tokenization: Find relevant papers and assess its impact. (Used in tokenization?
- Delve into transformer circuits: How can QK and OV be “decomposed” and “disentangled”?
- **Open Question:** Does Life2Vec include an MLP? If not, how and where are the neuron activations obtained?
- Is autointerpretability possible? Is it good? Anyhow, how is it possible to see what maximally activates a specific feature based on input for L2V???

---

## SAE Resources

- [GitHub of SAE training code](https://github.com/ai-safety-foundation/sparse_autoencoder)
- [ARENA course and exercises (recommended by Neel)](https://arena-chapter0-fundamentals.streamlit.app/)
