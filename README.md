# roads_semantic_segmentation
Semantic segmentation of roads on satellite images. Training U-Net on open source Massachusetts Roads Dataset.

This project performs U-Net model (from segmentation_models_pytorch) with imagenet50 decoder, trained on open source Massachusetts Roads Dataset (https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset).

The best developed metrics: dice_loss - 0.03421, fscore - 0.973, iou_score - 0.9479 on the test, after 40 epochs.

It is jupyter (kaggle) notebook, all cells can be run in the order. 

!!! Best models are NOT presented in the repository, as they are too large.

