\# BrailleVision-XAI

An Explainable Multi-Stage Braille Recognition and Decoding Framework



\---



\# Overview



BrailleVision-XAI is a research-oriented deep learning framework designed for Braille character detection, sentence reconstruction, explainable AI analysis, and post-processing refinement.



This repository documents the progressive evolution of a multi-stage Braille recognition system combining:



\- YOLOv8-based Braille detection

\- Proposal refinement using sliding-window analysis

\- AttentionCNN-based grid classification

\- Explainable AI visualization pipelines

\- SymSpell and transformer-based correction

\- Cognitive/thematic sentence analysis

\- Structured benchmarking and ablation studies



The repository is intentionally organized as a sequence of research notebooks that preserve the experimental progression of the framework rather than exposing only a final black-box model.



This project is currently maintained as a research architecture repository intended for publication, collaboration, and future extension.



\---



\# Final System Architecture



<p align="center">

&#x20; <img src="assets/architecture/Final-Design-Diagram.png" width="320"/>

</p>



\---



\# Repository Structure



```text

BrailleVision-XAI/

│

├── notebooks/

│   │

│   ├── core\_pipeline/

│   │   ├── 01\_braille\_foundation.ipynb

│   │   ├── 02\_braille\_sentence\_pipeline.ipynb

│   │   ├── 03\_detection\_and\_grid\_alignment.ipynb

│   │   ├── 04\_attention\_xai\_pipeline.ipynb

│   │   │

│   │   └── context/

│   │       ├── 01\_context.txt

│   │       ├── 02\_context.txt

│   │       ├── 03\_context.txt

│   │       └── 04\_context.txt

│   │

│   ├── experiments/

│   │   ├── 05\_ablation\_framework.ipynb

│   │   ├── 06\_results\_and\_visualization.ipynb

│   │   │

│   │   └── context/

│   │       ├── 05\_context.txt

│   │       └── 06\_context.txt

│

├── assets/

│   └── architecture/

│       ├── sequence.png

│       ├── Braiille-PipeLine-Fuzzy-Added.png

│       ├── component-Interaction-Diagram.png

│       ├── Final-Design-Diagram.png

│       └── high\_level\_architecture.png

│

└── README.md

```



\---



\# Canonical Pipeline



The primary pipeline explored throughout this project is:



```text

Input Source

&#x20;   ↓

YOLOv8 Detection

&#x20;   ↓

Proposal Refinement

&#x20;   ↓

AttentionCNN Grid Classification

&#x20;   ↓

Explainability Layer (XAI)

&#x20;   ↓

Post-Processing \& Correction

&#x20;   ↓

Structured Evaluation \& Benchmarking

```



\---



\# Notebook Progression



| Notebook | Purpose | Main Techniques | Outputs |

|---|---|---|---|

| 01 Braille Foundation | Foundational Braille detection and evaluation | Dot mapping, clustering, uncertainty tracking | Detection overlays, accuracy logs |

| 02 Sentence Pipeline | Sentence-level reconstruction and semantic correction | SymSpell, ByT5, spacing analysis | Corrected sentences |

| 03 Detection \& Grid Alignment | Spatial refinement and proposal correction | Soft-NMS, RPN snapping, tiling | Grid-aligned decoding |

| 04 Attention XAI Pipeline | Explainable AI verification framework | AttentionCNN, heatmaps, confidence maps | Character explanations |

| 05 Ablation Framework | Comparative benchmarking pipeline | Multi-method evaluation, logging | Ablation reports |

| 06 Results \& Visualization | Experimental aggregation and reporting | Metrics plotting, collages | Publication-ready visualizations |



\---



\# Recommended Reading Paths



\## Full Pipeline Understanding

`01 → 02 → 03 → 04 → 05 → 06`



\## Explainable AI \& Interpretability

`04 → 06`



\## Benchmarking \& Experimental Evaluation

`05 → 06`



\## NLP \& Sentence Reconstruction

`02 → 04`



\---



\# Core Features



\- YOLOv8-based Braille cell localization

\- Sliding-window proposal refinement

\- Adaptive row clustering and spacing estimation

\- Soft-NMS overlap preservation

\- RPN-based Braille grid alignment

\- AttentionCNN explainability framework

\- Dot-level confidence visualization

\- Transformer-assisted sentence refinement

\- SymSpell dictionary correction

\- Cognitive and thematic text analysis

\- TTS-assisted interactive reading

\- Structured benchmarking framework

\- Publication-oriented result visualization



\---



\# Research Objectives



This project explores:



\- Robust Braille recognition under noisy layouts

\- Explainable AI for assistive vision systems

\- Hybrid symbolic + deep learning decoding pipelines

\- Sentence-level semantic refinement

\- Spatially-aware Braille reconstruction

\- Human-interpretable confidence analysis

\- Comparative evaluation of decoding strategies



\---



\# Experimental Design Philosophy



Rather than exposing only a final optimized model, this repository preserves the research and engineering progression of the framework.



The notebooks intentionally document:



\- foundational baselines

\- iterative refinements

\- experimental branches

\- ablation studies

\- explainability mechanisms

\- evaluation methodologies



This structure improves:

\- reproducibility

\- transparency

\- interpretability

\- future extensibility



\---



\# Important Repository Note



This repository intentionally does \*\*not\*\* include:



\- trained model weights

\- datasets

\- proprietary experimental assets

\- deployment packages

\- large-scale generated outputs



The repository is designed as a structured research architecture and experimental framework accompanying ongoing academic work and planned publication efforts.



Researchers, collaborators, or contributors interested in extending the framework or discussing potential collaboration are encouraged to reach out directly.



\---



\# Current Research Focus



Current areas of investigation include:



\- explainable Braille recognition systems

\- proposal refinement for dense Braille layouts

\- attention-guided grid verification

\- semantic reconstruction under noisy detection

\- assistive AI accessibility systems

\- hybrid symbolic-neural reasoning pipelines



\---



\# Future Directions



Potential future extensions include:



\- multilingual Braille support

\- lightweight edge deployment

\- real-time mobile inference

\- graph-based spatial reasoning

\- transformer-native decoding

\- reinforcement-guided correction pipelines

\- multimodal accessibility interfaces



\---



\# Citation



If you use this repository in research or academic work, please cite appropriately after official publication.



\---



\# Author



Developed as a research-focused Braille recognition and explainability framework exploring the intersection of:



\- Computer Vision

\- Explainable AI

\- Natural Language Processing

\- Assistive Intelligence Systems

\- Spatial Reasoning Frameworks

\- Human-Centered AI

