# Computer Vision exercise for Deep Learning Lab 2023 at University of Freiburg. 
Check [Deep Learning Lab 24 - Exercise 3.pdf](https://github.com/ErlisLushtaku/DeepLearningLab-ComputerVision/blob/main/Deep%20Learning%20Lab%2024%20-%20Exercise%203.pdf) for a detailed description of the task. Check [Report.pdf](https://github.com/ErlisLushtaku/DeepLearningLab-ComputerVision/blob/main/Report.pdf) to see the plots, visualizations, answers to the exercise questions and the results.

The project includes the following parts:
- Image Matching: Used pretrained DINOv2 features for nearest-neighbor matching, comparing negative feature-space distance and cycle distance as scoring methods, with and without PCA.
- Image Captioning: Used the [BLIP](https://arxiv.org/abs/2201.12086) model, experimenting with greedy search, top-k sampling, and prompt engineering to improve BLEU score.
- Image-Text Retrieval: Evaluated image-text retrieval with BLIP, and trained the retrieval head from scratch.
