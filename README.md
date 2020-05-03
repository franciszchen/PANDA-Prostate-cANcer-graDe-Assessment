# [PANDA](https://www.kaggle.com/c/prostate-cancer-grade-assessment)-Prostate-cANcer-graDe-Assessment

## Experiment #1 (0.47 on public LB)
- Used model: DenseNet121, trained from scratch
- No image augmentations
- Other settings:
  - Image size: 256 x 256 size patches of original image
  - No CV
  - 20 epochs
  - Batch size: 16 images

## Experiment #2 (0.51 on public LB)
- Used model: DenseNet121, pre-trained ImageNet weights
- Basic shift, scale, rotation and flips
- Other settings:
  - Image size: 256 x 256 size patches of original image
  - No CV
  - 25 epochs
  - Batch size: 16 images

## Experiment #3 (0.59 on public LB)
- Used model: DenseNet121, pre-trained ImageNet weights
- Basic shift, scale, rotation and flips
- Other settings:
  - Image size: 256 x 256 size patches of original image
  - 5 Fold CV
  - 25 epochs
  - Batch size: 16 images

## Experiment #4 (0.51 on public LB)
- Used model: DenseNet121, pre-trained ImageNet weights
- Basic shift, scale, rotation and flips
- Other settings:
  - Trained on Gleason score instead of directly on ISUP grades
  - Image size: 256 x 256 size patches of original image
  - No CV
  - 25 epochs
  - Batch size: 16 images
