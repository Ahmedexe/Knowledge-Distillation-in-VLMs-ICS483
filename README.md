# ICS483 - Project: The Professor: MultiTeacher PromptKD

PromptKD (CVPR 2024) distills knowledge from a single large CLIP teacher to a smaller
student using prompt learning on unlabeled images. However, different teacher models
capture complementary visual representations. We propose to extend PromptKD with
multi-teacher distillation, combining knowledge from two CLIP teachers (ViT-L/14 and
ViT-B/32) to train a more robust student. We will explore combination strategies
including prediction averaging and confidence-based weighting. The hypothesis is that
multi-teacher supervision improves generalization to novel classes. We evaluate on four
diverse datasets (Caltech101, DTD, UCF101, EuroSAT) to demonstrate cross-domain
benefits compared to single-teacher PromptKD.

- [[Source Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Li_PromptKD_Unsupervised_Prompt_Distillation_for_Vision-Language_Models_CVPR_2024_paper.html)]

- [[Official Source Github](https://github.com/zhengli97/PromptKD)]

- [[Used Dataset](https://huggingface.co/zhengli97/prompt_learning_dataset)]


> Team members: Omar Alkhulaif, Ahmed Alzuhair, Ahmed Algadhi
