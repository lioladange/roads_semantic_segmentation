# roads_semantic_segmentation
Semantic segmentation of roads on satellite images. Training UNET on open source Massachusetts Roads Dataset.

This project outperforms UNET model (from segmentation_models_pytorch) woith imagenet50 decoder trainig on open source Massachusetts Roads Dataset (https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset).
The best developed parameters: dice_loss - 0.03421, fscore - 0.973, iou_score - 0.9479 on the test, after 40 epochs.

It is jupyter (kaggle) notebook, all cells can be run in the order. Best models are presented in the repository. 

