# Awesome Gesture Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Awesome **Gesture Generation** resources inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

<img alt="" src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMTgiIHZpZXdCb3g9IjAgMCAyNCAxOCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTIzLjU2MDYgMC42NjI0MTJDMjMuODQyIDAuOTQ0MTE4IDI0IDEuMzI1OTggMjQgMS43MjQxM0MyNCAyLjEyMjI3IDIzLjg0MiAyLjUwNDE0IDIzLjU2MDYgMi43ODU4NEw5LjAzNzE0IDE3LjMwOTNDOC43NTU0MyAxNy41OTA3IDguMzczNTcgMTcuNzQ4NyA3Ljk3NTQyIDE3Ljc0ODdDNy41NzcyOCAxNy43NDg3IDcuMTk1NDEgMTcuNTkwNyA2LjkxMzcxIDE3LjMwOTNMMC40MDMxODcgMTAuNzk4OEMwLjEzNzk0MSAxMC41MTM4IC0wLjAwNjQ5OTY0IDEwLjEzNzEgMC4wMDAyMjQ2NzUgOS43NDc4NEMwLjAwNjk0ODk5IDkuMzU4NTcgMC4xNjQzMTQgOC45ODcwNyAwLjQzOTI0NSA4LjcxMTQyQzAuNzE0ODk3IDguNDM2NDkgMS4wODY0IDguMjc5MTIgMS40NzU2NiA4LjI3MjRDMS44NjQ5MiA4LjI2NTY4IDIuMjQxNjMgOC40MTAxMiAyLjUyNjYyIDguNjc1MzZMNy45NzU0MiAxNC4xMjQyTDIxLjQzNzIgMC42NjI0MTJDMjEuNzE4OSAwLjM4MTA1NyAyMi4xMDA3IDAuMjIzMDIyIDIyLjQ5ODkgMC4yMjMwMjJDMjIuODk3IDAuMjIzMDIyIDIzLjI3ODkgMC4zODEwNTcgMjMuNTYwNiAwLjY2MjQxMloiIGZpbGw9IiMwMDhDMzgiLz4KPC9zdmc+Cg==" />

## Table of Contents

- [1. Survey](#survey)
- [2. Papers](#papers)
  - [Fundamental Paper](#fundamental)
  - [GENEA Challenge](#genea)
  - [2023](#2023)
  - [2022](#2022)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
  - [Others](#others)
- [3. Dataset](#dataset)
- [4. Toolkit](#toolkit)
- [5. Talks](#talks)
- [6. Code](#implementations)
- [Contributing](#contributing)

---

**PapersWithCode**

- Gesture Generation : [https://paperswithcode.com/task/gesture-generation](https://paperswithcode.com/task/gesture-generation)

## <a name="survey">1. Survey</a>

<details open>
<summary>Comprehensive preview</summary>

- [A Comprehensive Review of Data-Driven Co-Speech Gesture Generation](https://arxiv.org/abs/2301.05339) | [github](https://github.com/google/mipnerf) | [web](https://www.ea.com/seed/news/genea-challenge-2022)

</details>

<details open>
<summary>GENEA Challenge</summary>

- [The GENEA Challenge 2022: A large evaluation of data-driven co-speech gesture generation](https://arxiv.org/abs/2208.10441) | [homepage](https://youngwoo-yoon.github.io/GENEAchallenge2022/) | [video](https://www.youtube.com/watch?v=4n02wXGGnd0)

- [GENEA Workshop 2021: The 2nd Workshop on Generation and Evaluation of Non-verbal Behaviour for Embodied Agents](https://dl.acm.org/doi/10.1145/3462244.3480983) | [homepage](https://genea-workshop.github.io/2021/)

- [The GENEA Challenge 2020: A large, crowdsourced evaluation of gesture generation systems on common data](https://arxiv.org/abs/2102.11617) | [homepage](https://svito-zar.github.io/GENEAchallenge2020/) | [video](https://www.youtube.com/watch?v=QmaoKRzoVwM) | [github](https://github.com/Svito-zar/genea_numerical_evaluations)
</details>

## <a name="papers">2. Papers</a>

<!-- ************************* Base-paper ************************* -->
<details open>
<summary><a name="fundamental">Fundamental Paper</a></summary>

- [The Relation of Speech and Gestures: Temporal Synchrony Follows Semantic Synchrony](https://core.ac.uk/download/pdf/15945024.pdf)
- [Complexity Matters E05: Complexity Matching and Synchronization between Gestures and Speech](https://www.youtube.com/watch?v=lMb-So8wKS8)

</details>
<!-- ************************* Base-paper ************************* -->

---

<!-- ************************* GENEA Challenge ************************* -->
<details open>
<summary><a name="genea">GENEA Challenge</a></summary>

- **2023 - Accepted papers**

  - [Evaluating Data-Driven Co-Speech Gestures of Embodied Conversational Agents through Real-Time Interaction](https://arxiv.org/abs/2210.06974) | [web](https://www.ea.com/seed/news/evaluating-data-driven-co-speech-gestures) 

- **2022 - Accepted papers**

<img src="data:image/png;base64,PHN2ZyB3aWR0aD0iMTIiIGhlaWdodD0iOSIgdmlld0JveD0iMCAwIDEyIDkiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxwYXRoIGQ9Ik0xMS43Nzk5IDAuMjE5OTVDMTEuOTIwNCAwLjM2MDU3NiAxMS45OTkzIDAuNTUxMiAxMS45OTkzIDAuNzQ5OTVDMTEuOTk5MyAwLjk0ODcwMSAxMS45MjA0IDEuMTM5MzMgMTEuNzc5OSAxLjI3OTk1TDQuNTI5OTQgOC41Mjk5NUM0LjM4OTMyIDguNjcwNCA0LjE5ODY5IDguNzQ5MjkgMy45OTk5NCA4Ljc0OTI5QzMuODAxMTkgOC43NDkyOSAzLjYxMDU3IDguNjcwNCAzLjQ2OTk0IDguNTI5OTVMMC4yMTk5NDQgNS4yNzk5NUMwLjA4NzUzNTcgNS4xMzc2OSAwLjAxNTQzMjIgNC45NDk2NCAwLjAxODc4ODkgNC43NTUzMkMwLjAyMjE0NTYgNC41NjEgMC4xMDA3MDEgNC4zNzU1NSAwLjIzNzk0NCA0LjIzNzk1QzAuMzc1NTQ4IDQuMTAwNzEgMC41NjA5OTcgNC4wMjIxNSAwLjc1NTMxNCA0LjAxODhDMC45NDk2MzEgNC4wMTU0NCAxLjEzNzY4IDQuMDg3NTQgMS4yNzk5NCA0LjIxOTk1TDMuOTk5OTQgNi45Mzk5NUwxMC43MTk5IDAuMjE5OTVDMTAuODYwNiAwLjA3OTQ5OTcgMTEuMDUxMiAwLjAwMDYxMDM1MiAxMS4yNDk5IDAuMDAwNjEwMzUyQzExLjQ0ODcgMC4wMDA2MTAzNTIgMTEuNjM5MyAwLjA3OTQ5OTcgMTEuNzc5OSAwLjIxOTk1WiIgZmlsbD0iIzAwOEMzOCIvPgo8L3N2Zz4K">

| Menthod     | Description |  |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

  - [The DeepMotion entry to the GENEA Challenge 2022](https://dl.acm.org/doi/abs/10.1145/3536221.3558059)
  - [The IVI Lab entry to the GENEA Challenge 2022 – A Tacotron2 Based Method for Co-Speech Gesture Generation With Locality-Constraint Attention Mechanism](https://dl.acm.org/doi/abs/10.1145/3536221.3558060)
  - [Exemplar-based Stylized Gesture Generation from Speech: An Entry to the GENEA Challenge 2022 ](https://openreview.net/forum?id=fO_Q4q1dFAA)
  - [UEA Digital Humans entry to the GENEA Challenge 2022](https://openreview.net/forum?id=RZP6nErM2Xa)
  - [GestureMaster: Graph-based Speech-driven Gesture Generation](https://dl.acm.org/doi/10.1145/3536221.3558063) | [video](https://www.youtube.com/watch?v=nwNwEGX33SA)
  - [ReCell: replicating recurrent cell for auto-regressive pose generation](https://openreview.net/forum?id=uX86IlhiHNx)
  - [The ReprGesture entry to the GENEA Challenge 2022](https://openreview.net/forum?id=atWaELmguNj7)
  - [TransGesture: Autoregressive Gesture Generation with RNN-Transducer](https://openreview.net/forum?id=AYMDEx97qPN)
  - [Hybrid Seq2Seq Architecture for 3D Co-Speech Gesture Generation](https://openreview.net/forum?id=-2HZD-e6pX7W) | [github](https://github.com/youngwoo-yoon/Co-Speech_Gesture_Generation)

- **2021 - Accepted papers**

  - [Probabilistic Human-like Gesture Synthesis from Speech using GRU-based WGAN](https://openreview.net/forum?id=ykvm7OLh7B) | [video](https://www.youtube.com/watch?v=PMhjX6cdIPE)
  - [Influence of Movement Energy and Affect Priming on the Perception of Virtual Characters Extroversion and Mood](https://openreview.net/forum?id=GjjPtEVdSLB)
  - [Crossmodal clustered contrastive learning: Grounding of spoken language to gesture](https://openreview.net/forum?id=o8CpxaBurZQ) | [github](https://github.com/dondongwon/CC_NCE_GENEA)

- **2020 - Accepted papers**
  - [The StyleGestures entry to the GENEA Challenge 2020](https://genea-workshop.github.io/2020/downloads/Alexanderson2020StyleGestures.pdf) | [zendomo](https://zenodo.org/record/4088600#.ZBqRWNJByV4)
  - [The FineMotion entry to the GENEA Challenge 2020](https://zenodo.org/record/4088609#.ZBqSB9JByV4)
  - [Double-DCCCAE: Estimation of Sequential Body Motion Using Wave-Form - AlltheSmooth](https://zenodo.org/record/4088376#.ZBqR89JByV4)
  - [CGVU: Semantics-guided 3D Body Gesture Synthesis](https://zenodo.org/record/4090879#.ZBqSHtJByV4)
  - [Interpreting and Generating Gestures with Embodied Human Computer Interactions](https://zenodo.org/record/4088625#.ZBqSLtJByV4)
  - [The Nectec Gesture Generation System entry to the GENEA Challenge 2020](https://zenodo.org/record/4088629#.ZBqSQ9JByV4)s

</details>
<!-- ************************* GENEA Challenge ************************* -->

---

<!-- ************************* Kaggle ************************* -->
<details open>
<summary><a name="kaggle"><bold>Kaggle Ranking</bold></a></summary>

- **TED Gesture Dataset**

  - [Learning Hierarchical Cross-Modal Association for Co-Speech Gesture Generation](https://arxiv.org/pdf/2203.13161.pdf) [github](https://github.com/alvinliu0/HA2G) | [video]() | [homepage](https://alvinliu0.github.io/projects/HA2G)
  - [Rhythmic Gesticulator: Rhythm-Aware Co-Speech Gesture Synthesis with Hierarchical Neural Embeddings](https://arxiv.org/abs/2210.01448) | [github](https://github.com/aubrey-ao/humanbehavioranimation) | [video](https://www.youtube.com/watch?v=qy2MrNhsoIs)
  - [Speech2AffectiveGestures: Synthesizing Co-Speech Gestures with Generative Adversarial Affective Expression Learning](https://arxiv.org/abs/2108.00262v2) [github](https://github.com/UttaranB127/speech2affective_gestures) | [homepage](https://gamma.umd.edu/researchdirections/affectivecomputing/affagents/s2ag/) | [video](https://www.youtube.com/watch?v=D_w1FtIVvQ8)
  - [Speech Gesture Generation from the Trimodal Context of Text, Audio, and Speaker Identity](https://arxiv.org/abs/2009.02119v1) [github](https://github.com/ai4r/Gesture-Generation-from-Trimodal-Context) | [github](https://github.com/PantoMatrix/BEAT)
  - [Speech2AffectiveGestures: Synthesizing Co-Speech Gestures with Generative Adversarial Affective Expression Learning](https://arxiv.org/abs/2108.00262v2) [github](https://github.com/UttaranB127/speech2affective_gestures)

- **BEAT**
  - [BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis](https://arxiv.org/abs/2203.05297v5) | [github](https://github.com/PantoMatrix/BEAT)
  - [Speech Gesture Generation from the Trimodal Context of Text, Audio, and Speaker Identity](https://arxiv.org/abs/2009.02119v1) | [github](https://github.com/ai4r/Gesture-Generation-from-Trimodal-Context)
  - [Audio2Gestures: Generating Diverse Gestures from Speech Audio with Conditional Variational Autoencoders](https://arxiv.org/abs/2108.06720v1)
  - [Learning Individual Styles of Conversational Gesture](https://github.com/amirbar/speech2gesture)
  - [Robots Learning to Say `No': Prohibition and Rejective Mechanisms in Acquisition of Linguistic Negation](https://arxiv.org/abs/1810.11804v1)

</details>
<!-- ************************* Kaggle ************************* -->

---

<!-- ************************* 2023 ************************* -->
<details open>
<summary><a name="2023">2023</a></summary>

- [A Comprehensive Review of Data-Driven Co-Speech Gesture Generation](https://arxiv.org/abs/2301.05339) | [github](https://github.com/google/mipnerf) | [web](https://www.ea.com/seed/news/genea-challenge-2022)
- []()
- []()
- []()
</details>
<!-- ************************* 2023 ************************* -->

---

<!-- ************************* 2022 ************************* -->
<details open>
<summary><a name="2022">2022</a></summary>

- [Evaluating Data-Driven Co-Speech Gestures of Embodied Conversational Agents through Real-Time Interaction](https://arxiv.org/abs/2104.10078)
- [ZeroEGGS: Zero-shot Example-based Gesture Generation from Speech](https://arxiv.org/abs/2209.07556) | [github](https://github.com/ubisoft/ubisoft-laforge-ZeroEGGS) | [video](https://www.youtube.com/watch?v=EJPdTtVrxHo)
- [Voice2Face: Audio-Driven Facial and Tongue Rig Animations](https://media.contentapi.ea.com/content/dam/ea/seed/presentations/seed-sca2022-voice2face-paper.pdf) | [video](https://www.youtube.com/watch?v=R4CWYAQe4Zs) | [web](https://www.ea.com/seed/news/sca22-voice2face-audio-driven-facial-animation)
- [Deep Gesture Generation for Social Robots Using Type-Specific Libraries](https://arxiv.org/abs/2210.06790) | [video](https://www.youtube.com/watch?v=R4CWYAQe4Zs) | [web](https://www.ea.com/seed/news/sca22-voice2face-audio-driven-facial-animation)
- [The DeepMotion entry to the GENEA Challenge 2022](https://dl.acm.org/doi/abs/10.1145/3536221.3558059)
- [Automatic text‐to‐gesture rule generation for embodied conversational agents](https://onlinelibrary.wiley.com/doi/abs/10.1002/cav.1944) [video](https://www.youtube.com/watch?v=GIxaI9yTmMc)
- [Gesture2Vec: Clustering Gestures using Representation Learning Methods for Co-speech Gesture Generation](https://sfumars.com/wp-content/papers/2022_iros_gesture2vec.pdf) [github](https://github.com/pjyazdian/Gesture2Vec) | [video](https://www.youtube.com/watch?v=ac8jWk4fdCU) | [video](https://www.youtube.com/watch?v=qFObMpOboCg)

</details>
<!-- ************************* 2022 ************************* -->

---

<!-- ************************* 2021 ************************* -->
<details open>
<summary><a name="2021">2021</a></summary>

- [Evaluating Data-Driven Co-Speech Gestures of Embodied Conversational Agents](https://dl.acm.org/doi/abs/10.1145/3514197.3549697)
- [Multimodal analysis of the predictability of hand-gesture properties](https://arxiv.org/abs/2108.05762)
- [Deep Gesture Generation for Social Robots Using Type-Specific Libraries](https://arxiv.org/abs/2210.06790)
- [A Framework for Integrating Gesture Generation Models into Interactive Conversational Agents](https://arxiv.org/abs/2102.12302) | [video] (https://www.youtube.com/watch?v=jhgUBS0125A) | [homepage](https://nagyrajmund.github.io/project/gesturebot/) | [github](https://github.com/nagyrajmund/gesturebot)
- [Speech2Properties2Gestures: Gesture-Property Prediction as a Tool for Generating Representational Gestures from Speech](https://arxiv.org/abs/2106.14736) | [homepage](https://svito-zar.github.io/speech2properties2gestures/)
- [Moving Fast and Slow: Analysis of Representations and Post-Processing in Speech-Driven Automatic Gesture Generation](https://www.tandfonline.com/doi/full/10.1080/10447318.2021.1883883)
- []()
- []()
- []()
</details>
<!-- ************************* 2021 ************************* -->

---

<!-- ************************* 2020 ************************* -->
<details open>
<summary><a name="2020">2020</a></summary>

- [The GENEA Challenge 2020: A large, crowdsourced evaluation of gesture generation systems on common data](https://arxiv.org/abs/2102.11617) | [homepage](https://svito-zar.github.io/GENEAchallenge2020/) | [video](https://www.youtube.com/watch?v=QmaoKRzoVwM) | [video](https://www.youtube.com/watch?v=Y-5dgBQk34c) | [github](https://github.com/Svito-zar/genea_numerical_evaluations)
- [Gesticulator: A framework for semantically-aware speech-driven gesture generation](https://arxiv.org/abs/2001.09326) | | [video](https://www.youtube.com/watch?v=VQ8he6jjW08) | [github](https://github.com/Svito-zar/gesticulator) | [homepage](https://svito-zar.github.io/gesticulator/) | [dataset](https://figshare.com/projects/Gesticulator/87128)
- [Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows]() | [video](https://www.youtube.com/watch?v=egf3tjbWBQE) | [github](https://github.com/simonalexanderson/StyleGestures)
- [Probabilistic Multi-modal Interlocutor-awa\*re Generation of Facial Gestures in Dyadic Settings](https://arxiv.org/abs/2006.09888) | [video](https://www.youtube.com/watch?v=RhazMS4L_bk) | [homepage](https://jonepatr.github.io/lets_face_it/)
- [Can we trust online crowdworkers? Comparing online and offline participants in a preference test of virtual agents](https://arxiv.org/pdf/2009.10760.pdf)
- []()
- []()

</details>  
<!-- ************************* 2020 ************************* -->

---

<!-- ************************* 2019 ************************* -->
<details open>
<summary><a name="2019">2019</a></summary>

- [Analyzing Input and Output Representations for Speech-Driven Gesture Generation](https://arxiv.org/abs/1903.03369) | [github](https://github.com/GestureGeneration/Speech_driven_gesture_generation_with_autoencoder) | [video](https://www.youtube.com/watch?v=Iv7UBe92zrw) | [video](https://www.youtube.com/watch?v=tQLVyTVtsSU) | [homepage](https://svito-zar.github.io/audio2gestures/)
- [On the Importance of Representations for Speech-Driven Gesture Generation](https://www.ifaamas.org/Proceedings/aamas2019/pdfs/p2072.pdf)
- []()
- []()

</details>
<!-- ************************* 2019 ************************* -->

---

<!-- ************************* 2018 ************************* -->
<details open>
<summary><a name="2018">2018</a></summary>

- [A Neural Network Approach to Missing Marker Reconstruction in Human Motion Capture](https://arxiv.org/abs/1803.02665) | [video](https://www.youtube.com/watch?v=mi75gzEhbHI) | [video](https://www.youtube.com/watch?v=MFdFqxCNhN0) | [github](https://github.com/Svito-zar/NN-for-Missing-Marker-Reconstruction)
- [Data Driven Non-Verbal Behavior Generation for Humanoid Robots](https://dl.acm.org/doi/10.1145/3242969.3264970)
- [A Neural Network Approach to Missing Marker Reconstruction in Human Motion Capture](https://www.researchgate.net/publication/323626902_A_Neural_Network_Approach_to_Missing_Marker_Reconstruction_in_Human_Motion_Capture) | [github](https://github.com/Svito-zar/NN-for-Missing-Marker-Reconstruction) | [video](https://www.youtube.com/watch?v=mi75gzEhbHI)

- []()
</details>
<!-- ************************* 2018 ************************* -->

---

<!-- ************************* <2017 ************************* -->
<details open>
<summary><a name="2017"><2017</a></summary>

- []()
</details>
<!-- ************************* <2017 ************************* -->

---

<!-- ************************* Others ************************* -->
<details open>
<summary><a name="others">Others</a></summary>

- [Rig Inversion by Training a Differentiable Rig Function](https://arxiv.org/abs/2301.09567) | [video](https://www.youtube.com/watch?v=sYCz9LGIkuI)
</details>
<!-- ************************* Others ************************* -->

## <a name="dataset">Datasets</a>

- [PATS Dataset](https://chahuja.com/pats/)

## <a name="talks">Talks</a>

## <a name="toolkit">Toolkit</a>

- Algorithms
  - [SGToolkit: An Interactive Gesture Authoring Toolkit for Embodied Conversational Agents](https://github.com/ai4r/SGToolkit) | [homepage](https://uist.acm.org/uist2021/) | [video](https://www.youtube.com/watch?v=qClSOtLiVlc)

## Books

- []()

## Websites

- []()

## Talks

- [GDC 2020 - Machine Learning, Physics Simulation, Kolmogorov Complexity, and Squishy Bunnies](https://www.youtube.com/watch?v=sUb0W5_waRI)
- []()

# Contributing

## Implementations

#### Tensorflow

- []()

#### PyTorch

- []()

## License

MIT
