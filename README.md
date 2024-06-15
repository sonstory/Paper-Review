# Paper-Review
### 고려대학교 산업경영공학과 DSBA 연구실(지도교수 : 강필성 교수님) 석사과정 손준영(junyeong_son@korea.ac.kr)
- 인공지능 및 딥러닝에 관해 석사 과정 기간 동안 관심 분야 논문을 읽고, 정리했습니다.
- 리뷰 내용에 관해 수정해야하거나, 궁금한 부분 있으시다면 이메일을 통해 연락 바랍니다.
- 깃허브 링크의 경우 오피셜 코드가 아닐 수 있습니다.
- [YOUTUBE] 링크에는 [DSBA 연구실 유튜브](https://www.youtube.com/@dsba2979)에서 제가 리뷰한 영상을 포함했습니다.

# Reserach Interest
- `Vision-Language Pretrained Model(VLM)`
- `Lightweight Image Captioning Model`
- `Parameter-Efficient Fine-Tuning(PEFT)` using `Adapter`

# ① Vision-Language Pretrained Model
- Align before Fuse: Vision and Language Representation Learning with Momentum Distillation(NeurIPS 2021 Spotlight) [[PAPER]](https://arxiv.org/abs/2107.07651) [[GITHUB]](https://github.com/salesforce/ALBEF) [[REVIEW]](https://junyeongson.notion.site/Align-before-Fuse-Vision-and-Language-Representation-Learning-with-Momentum-Distillation-599c983674f443a89b5c92505e27e545?pvs=4)
- SimVLM: Simple Visual Language Model Pretraining with Weak Supervision(ICLR 2022) [[PAPER]](https://arxiv.org/abs/2108.10904)
- OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework(ICML 2022) [[PAPER]](https://arxiv.org/abs/2202.03052) [[GITHUB]](https://github.com/OFA-Sys/OFA?tab=readme-ov-file)
- CoCa: Contrastive Captioners are Image-Text Foundation Models(2022) [[PAPER]](https://arxiv.org/abs/2205.01917) [[REVIEW]](https://junyeongson.notion.site/CoCa-Contrastive-Captioners-are-Image-Text-Foundation-Models-e9f326397144468bb05d1b75f9a44e8a?pvs=4) [[YOUTUBE]](https://youtu.be/UwuY2WLE9l8?si=BRUsZZ2HK6_PFhg9)
- mPLUG: Effective and Efficient Vision-Language Learning by Cross-modal Skip-connections(EMNLP 2022) [[PAPER]](https://arxiv.org/abs/2205.12005) [[GITHUB]](https://github.com/X-PLUG/mPLUG)
- BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation(2022) [[PAPER]](https://arxiv.org/abs/2201.12086) [[GITHUB]](https://github.com/salesforce/LAVIS) [[REVEIW]](https://junyeongson.notion.site/BLIP-Bootstrapping-Language-Image-Pre-training-for-Unified-Vision-Language-Understanding-and-Genera-a829d1ec63f54dd8877f9ee1473aefc1?pvs=4)
- BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models(2023) [[PAPER]](https://arxiv.org/abs/2301.12597) [[GITHUB]](https://github.com/salesforce/LAVIS)
- Flamingo: a Visual Language Model for Few-Shot Learning [[PAPER]](https://arxiv.org/abs/2204.14198) [[REVIEW]](https://junyeongson.notion.site/Flamingo-a-Visual-Language-Model-for-Few-Shot-Learning-e264ce858050454e944e3f442deae82a?pvs=4) [[GITHUB]](https://github.com/lucidrains/flamingo-pytorch)
  
# ② Lightweight Image Captioning Model
- SmallCAP: Lightweight Image Captioning Prompted with Retrieval Augmentation(CVPR 2023) [[PAPER]](https://arxiv.org/abs/2209.15323) [[REVIEW]](https://junyeongson.notion.site/SMALLCAP-Lightweight-Image-Captioning-Prompted-with-Retrieval-Augmentation-866360c8cc0a4ebcbdef31b9fd43f0cc?pvs=4) [[GITHUB]](https://github.com/RitaRamo/smallcap)
- EVCAP: Retreival-Augmented Image Captioning with External Visual-Name Memory for Open-World Comprehension(CVPR 2024) [[PAPER]](https://arxiv.org/abs/2311.15879) [[REVIEW]](https://junyeongson.notion.site/EVCAP-Retrieval-Augmented-Image-Captioning-with-External-Visual-Name-Memory-for-Open-World-Comprehe-51acc546f45f49269fc0556476e7223f?pvs=4) [[GITHUB]](https://github.com/Jiaxuan-Li/EVCap)

# ③ Parameter-Efficient Fine-Tuning(Adapter)
- VL-Adapter: Parameter-Efficient Transfer Learning for Vision-and-Language Tasks [[PAPER]](https://arxiv.org/abs/2112.06825) [[REVIEW]](https://junyeongson.notion.site/VL-Adapter-Parameter-Efficient-Transfer-Learning-for-Vision-and-Language-Tasks-1864581e9f1c4e1cb6342d449ffd99d1?pvs=4)
- MAGMA -- Multimodal Augmentation of Generative Models through Adapter-based Finetuning(EMNLP 2022) [[PAPER]](https://arxiv.org/abs/2112.05253) [[GITHUB]](https://github.com/Aleph-Alpha/magma?utm_source=catalyzex.com)
- LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention(ICLR 2024) [[PAPER]](https://arxiv.org/abs/2303.16199) [[REVIEW]](https://junyeongson.notion.site/LLaMA-Adapter-Efficient-Fine-tuning-of-Language-Models-with-Zero-init-Attention-5de06405e68042a59128a02e301498cf?pvs=4) [[GITHUB]](https://github.com/OpenGVLab/LLaMA-Adapter)
- LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model [[PAPER]](https://arxiv.org/abs/2304.15010) [[REVIEW]](https://junyeongson.notion.site/LLaMA-Adapter-V2-Parameter-Efficient-Visual-Instruction-Model-de194fe3727648a4b3c4e38151ae8af4?pvs=4) [[GITHUB]](https://github.com/OpenGVLab/LLaMA-Adapter)

# ④ Survey
- Deep Industrial Image Anomaly Detection: A Survey(2023) [[PAPER]](https://arxiv.org/abs/2301.11514) [[GITHUB]](https://github.com/m-3lab/awesome-industrial-anomaly-detection)
- Self-Supervised Anomaly Detection: A Survey and Outlook(2022) [[PAPER]](https://arxiv.org/abs/2205.05173) [[REVIEW]](https://junyeongson.notion.site/Self-Supervised-Anomaly-Detection-A-Survey-and-Outlook-da48b331905a414f9de73a35d4198240?pvs=4)
- Vision-Language Models for Vision Tasks: A Survey(2023) [[PAPER]](https://arxiv.org/abs/2304.00685)
- A survey of efficient fine-tuning methods for Vision-Language Models — Prompt and Adapter [[PAPER]](https://arxiv.org/pdf/2402.02242)
