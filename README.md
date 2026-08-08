# Multimodal Media Retrieval and Captioning System — Group 15

Cross-modal image–text retrieval and image captioning models trained on Flickr8k / Flickr30k, with Streamlit demo notebooks for deployment.

## Repository Structure

```
├── notebooks/
│   ├── Retrieval Models/          # R* retrieval architectures (ResNet/ViT + LSTM/Transformer)
│   │   └── Improved/              # Improved & Flickr30k retrieval variants
│   ├── Captioning Models/         # C* captioning architectures
│   │   └── Improved/              # Improved captioning variants
│   └── Training & Evaluation/     # Preprocessing, embeddings, baselines, Streamlit helpers
│
├── docs/
│   ├── Project Proposal/          # Project proposal PDF
│   ├── Final Project Report/      # Final written report
│   ├── Architecture Diagrams/     # System / model architecture diagrams
│   └── Additional Documentation/  # Supporting notes and docs
│
├── presentation/
│   └── Final Project Presentation.pptx
│
├── images/                        # Architecture figures & sample outputs
│
└── README.md
```

## Notebook Overview

| Folder | Contents |
|--------|----------|
| **Retrieval Models** | R2–R5 (ResNet/ViT encoders with LSTM, attention, BiLSTM, Transformer), CLIP-style loss experiments, similarity evaluation |
| **Captioning Models** | C1–C4 (ResNet/ViT + LSTM / Attention / GPT decoder) |
| **Training & Evaluation** | Flickr preprocessing, embedding generation, retrieval baselines, Streamlit deployment helpers |

## Docs & Deliverables

- **Project Proposal** — `docs/Project Proposal/`
- **Final Presentation** — `presentation/Final Project Presentation.pptx`
- **Final Report / Architecture Diagrams / Images** — folders reserved for remaining deliverables
