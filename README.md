Objective: To benchmark and compare ResNet50, EfficientNetB0, and ViT_B16 for image-based HAR.

Dataset: Stanford 40 Actions Dataset

~40 action classes.

~10,000 images.

Contains diverse human actions with various objects and backgrounds.

Methodology:

Transfer Learning: All models were pre-trained on ImageNet-1k and fine-tuned on the Stanford40 dataset.

Evaluation Metrics: Accuracy, Macro F1, Weighted F1, Mean Class F1, and Std. Dev. of F1 (to measure consistency across classes).
