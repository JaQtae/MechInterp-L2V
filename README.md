MSc. Human-Centered Artificial Intelligence, DTU Compute anno 2025. This concerns applying the SAE interpretability idea to the Life2Vec model and scrutinizing its inner workings and if they are indeed interpretable.

### Primary papers:
- [x] [Anthropic: Towards Monosemanticity (2023)](https://transformer-circuits.pub/2023/monosemantic-features)
- [x] [Anthropic: Scaling Monosemanticity (2024 follow-up)](https://transformer-circuits.pub/2024/scaling-monosemanticity/)
- [ ] 📖[Life2Vec (Nature): Using sequences of life-events to predict human lives (2023)](https://www.nature.com/articles/s43588-023-00573-5)
   - [ ] [BERT - Bidirectional Encoder Representation of Transformers](https://arxiv.org/pdf/1810.04805) 
   
# Resources
The checklist indicates if I have read (and appropriately understood) the subject matter of the related resource.

📖 Indiciates what I am currently reading.

- [ ] 📖[**Anthropic**: Update on SAE training regime(2024)](https://transformer-circuits.pub/2024/april-update/index.html#training-saes)
- [x] [**Anthropic**: Toy Models of Superposition (2022)](https://transformer-circuits.pub/2022/toy_model/index.html)
- [ ] [Sparse Crosscoders for Cross-Layer Features and Model Diffing (2024)](https://transformer-circuits.pub/2024/crosscoders/index.html)
- [x] [**Chris Olah** - Dark Matter of AI - MechInterp (2024)](https://transformer-circuits.pub/2024/july-update/index.html#dark-matter)
- [ ] [Privileged Bases in Transformer Residual Stream (2023)](https://transformer-circuits.pub/2023/privileged-basis/index.html)
- [ ] [Zoom In: An Introduction to Circuits](https://distill.pub/2020/circuits/zoom-in/)
- [x] [A Mathematical Framework for Transformer Circuits (2021)](https://transformer-circuits.pub/2021/framework/index.html)
- [ ] [The Geometry of Concepts: Sparse Autoencoder Feature Structure (2024)](https://arxiv.org/abs/2410.19750)
- [ ] [Scaling and Evaluating SAE's (2024)](https://arxiv.org/pdf/2406.04093)
- [ ] 📖[**Neel Nanda** - MechInterp (SAE) podcast (2024)](https://podcasts.apple.com/dk/podcast/neel-nanda-mechanistic-interpretability-sparse-autoencoders/id1510472996?i=1000679600572)
- [ ] [Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2 (2024)](https://arxiv.org/abs/2408.05147)
- [ ] [Trading off performance and human oversight in algorithmic policy: evidence from Danish college admissions (2024, Magnus)](https://arxiv.org/abs/2411.15348)
- [ ] [SAE's find highly interpretable features in LLM's (2023)](https://arxiv.org/pdf/2309.08600)
- [ ] [Transformer visualization via dictionary learning: contextualized embedding as linear superposition of transformer factors (2023)](https://arxiv.org/pdf/2103.15949)
- [ ] [Codebook features: Sparse and Discrete interpretability for neural networks (2023)](https://arxiv.org/pdf/2310.17230)
- [x] [**YouTube**: 3Blue1Brown - visual explanation of LLM and transformers (series)](https://www.youtube.com/watch?v=wjZofJX0v4M)
- [x] [**YouTube**: Welch Labs - Dark matter of AI](https://www.youtube.com/watch?v=UGO_Ehywuxc)
- [ ] [**OpenAI**: LLM can explain neurons in LLM](https://openaipublic.blob.core.windows.net/neuron-explainer/paper/index.html)
- [ ] [Efficient Estimation of Word Representation in Vector Space (2013)](https://arxiv.org/pdf/1301.3781)
- [ ] [**DeepMind**: Improving Dictionary Learning with Gated SAE's](https://arxiv.org/pdf/2404.16014)
- [ ] [Improving SAE's by SQRT-L1 and Removing lowest activating features (article)](https://www.lesswrong.com/posts/YiGs8qJ8aNBgwt2YN/improving-sae-s-by-sqrt-ing-l1-and-removing-lowest)
- [ ] [Scratchpads: Show your word - intermediate computation with LLM's (used in Anthropic) (2021)](https://arxiv.org/pdf/2112.00114)
- [ ] 📖[**Neel Nhanda**: An opinionated list of favourite papers v2 (2024)](https://www.alignmentforum.org/posts/NfFST5Mio7BCAQHPA/an-extremely-opinionated-annotated-list-of-my-favourite)
- [ ] [GitHub with MechInterp in LLM's - code and paper references](https://github.com/ruizheliUOA/Awesome-Interpretability-in-Large-Language-Models)

### Additional buzzwords, open questions, and stuff to look into
- *k*-top SAE, Gated SAE, JumpReLU (w.r.t. expensiveness of training SAE's, possibly also just better?? ~Nanda)
- GeLU > ReLU?
- SAE performance is hard to measure... How do people do it?
- Idea/thought : L2V embedding map looked somewhat periodic -- is there inherent structure here (t-SNE?) (probably not, very far fetched...)
- Causality, introspection regarding model specifications of L2V and relating to the overarching use of SAE seen so far...
- Byte-paired tokenization (find paper, understand it...)
- If L2V used is BERT, find paper, understand it more thoroughly...
- Deeper understanding on the whole circuit phenomenon regarding *QK* and *OV*, allegedly how you can "decompose" and "disentangle" the transformer model
- **Does L2V have MLP???** or how/where do we get the neuron activations from?





