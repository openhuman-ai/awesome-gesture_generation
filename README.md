# Awesome Gesture Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Awesome **Gesture Generation** resources inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
- [Talks](#talks)
- [Awesome Gesture_Generation](#awesome-gesture_generation)
  - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
  - [Audio](#audio)
- [Implementations](#implementations)
- [Resources](#resources)
  - [Books](#books)
  - [Newsletters](#newsletters)
  - [Podcasts](#podcasts)
  - [Websites](#websites)
- [Contributing](#contributing)

---

## <a name="algorithms-and-design-patterns">Algorithms and Design Patterns</a>

_Gesture_Generation implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms](https://github.com/tayllan/awesome-algorithms)._

- Algorithms
  - [algorithms](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms.
  - [gesture_generation-ds](https://github.com/prabhupant/Gesture_Generation-ds) - A collection of data structure and algorithms for coding interviews.
  - [sortedcontainers](https://github.com/grantjenks/Gesture_Generation-sortedcontainers) - Fast and pure-Gesture_Generation implementation of sorted collections.
  - [TheAlgorithms](https://github.com/TheAlgorithms/Gesture_Generation) - All Algorithms implemented in Gesture_Generation.
- Design Patterns
  - [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns.
  - [gesture_generation-patterns](https://github.com/faif/Gesture_Generation-patterns) - A collection of design patterns in Gesture_Generation.
  - [transitions](https://github.com/pytransitions/transitions) - A lightweight, object-oriented finite state machine implementation.

## Audio

_Libraries for manipulating audio and its metadata._

- Audio
  - [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
  - [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
  - [kapre](https://github.com/keunwoochoi/kapre) - Keras Audio Preprocessors.
  - [librosa](https://github.com/librosa/librosa) - Gesture_Generation library for audio and music analysis.
  - [matchering](https://github.com/sergree/matchering) - A library for automated reference audio mastering.
  - [mingus](http://bspaans.github.io/Gesture_Generation-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
  - [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Audio feature extraction, classification, segmentation and applications.
  - [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
  - [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework.
- Metadata
  - [beets](https://github.com/beetbox/beets) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
  - [eyeD3](https://github.com/nicfit/eyeD3) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
  - [mutagen](https://github.com/quodlibet/mutagen) - A Gesture_Generation module to handle audio metadata.
  - [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.

# Resources

Where to discover learning resources or new Gesture_Generation libraries.

## Books

- [Fluent Gesture_Generation](https://www.oreilly.com/library/view/fluent-Gesture_Generation/9781491946237/)
- [Think Gesture_Generation](https://greenteapress.com/wp/think-Gesture_Generation-2e/)

## Websites

- Tutorials
  - [Full Stack Gesture_Generation](https://www.fullstackGesture_Generation.com/)
  - [gesture_generation Cheatsheet](https://www.Gesture_Generationcheatsheet.org/)
  - [Real Gesture_Generation](https://realGesture_Generation.com)
  - [The Hitchhiker’s Guide to Gesture_Generation](https://docs.Gesture_Generation-guide.org/)
  - [Ultimate Gesture_Generation study guide](https://github.com/huangsam/ultimate-Gesture_Generation)
- Libraries
  - [Awesome Gesture_Generation @LibHunt](https://Gesture_Generation.libhunt.com/)
- Others
  - [gesture_generation ZEEF](https://Gesture_Generation.zeef.com/alan.richmond)
  - [gesture_generationic News](https://news.Gesture_Generation.sc/)
  - [What the f\*ck Gesture_Generation!](https://github.com/satwikkansal/wtfGesture_Generation)

<details open>
<summary>Multi-scale</summary>

- [Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields](https://jonbarron.info/mipnerf/), Barron et al., Arxiv 2021 | [github](https://github.com/google/mipnerf) | [bibtex](./citations/mipnerf.txt)
- [Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://jonbarron.info/mipnerf360/), Barron et al., Arxiv 2022 | [bibtex](./citations/mip-nerf-360.txt)
</details>

<details open>
<summary>Model Reconstruction</summary>

- [UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction](https://arxiv.org/abs/2104.10078), Oechsle et al., ICCV 2021 | [bibtex](./citations/unisurf.txt)
- [NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction](https://arxiv.org/abs/2106.10689), Wang et al., NeurIPS 2021 | [github](https://github.com/Totoro97/NeuS) | [bibtex](./citations/neus.txt)
- [Volume Rendering of Neural Implicit Surfaces](https://arxiv.org/abs/2106.12052), Yariv et al., NeurIPS 2021 | [github](https://github.com/ventusff/neurecon) | [bibtex](./citations/volsdf.txt)
</details>

<details open>
<summary>Depth Estimation</summary>

- [NerfingMVS: Guided Optimization of Neural Radiance Fields for Indoor Multi-view Stereo](https://weiyithu.github.io/NerfingMVS/), Wei et al., ICCV 2021 | [bibtex](./citations/NerfingMVS.txt)
</details>

<details open>
<summary>Robotics</summary>

- [3D Neural Scene Representations for Visuomotor Control](https://3d-representation-learning.github.io/nerf-dy/), Li et al., CoRL 2021 Oral | [bibtex](./citations/nerf-dy.txt)
- [Vision-Only Robot Navigation in a Neural Radiance World](https://arxiv.org/abs/2110.00168), Adamkiewicz et al., RA-L 2022 Vol.7 No.2 | [bibtex](./citations/vision-only.txt)
</details>

## Talks

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=LCTYRqW-ne8&t=10190s), Ben Mildenhall
- [Understanding and Extending Neural Radiance Fields](https://www.youtube.com/watch?v=nRyOzHpcr4Q&feature=emb_logo&ab_channel=cvprtum), Barron et al.
- [Towards Photorealism (2nd half)](https://youtu.be/Rd0nBO6--bM?t=1992), Vladlen Koltun
- [Neural Radiance Fields for View Synthesis](https://www.youtube.com/watch?v=dPWLybp4LL0), Matthew Tancik

# Contributing

## Implementations

#### Tensorflow

- [NeRF](https://github.com/bmild/nerf), Mildenhall et al., 2020 | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [Nerual-Radiance-Fields](https://www.kaggle.com/code/ritzraha/nerual-radiance-fields), [@ariG23498](https://twitter.com/ariG23498), [@ritwik_raha](https://twitter.com/ritwik_raha), 2022

#### PyTorch

- [NeRF-PyTorch](https://github.com/yenchenlin/nerf-pytorch), Yen-Chen Lin, 2020 | [bibtex](./citations/pytorch-nerf.txt)
- [NeRF-PyTorch-Lighting](https://github.com/kwea123/nerf_pl), [@kwea123](https://github.com/kwea123), 2020
- [NeRF-W](https://github.com/kwea123/nerf_pl/tree/nerfw), [@kwea123](https://github.com/kwea123), 2021

## License

MIT
