# Dataset for Sino-nom Character Localization Project

This repository includes several dataset folders, with each folder representing a different approach of data augmentation. 

## Overview
Each folder includes:
- <code>images</code> folder: Contains images from the dataset for training and validating the proposed model, organized into <code>train</code> and <code>val</code> folders.
- <code>labels</code> folder: Contains label for each of the images in <code>images</code> folder.

## Detail
- <code>wb_localization_dataset_original</code>: The original dataset provided by lecturer.
- <code>wb_localization_dataset_set1</code>: The dataset after applying data augmentation on images containing white character on squared black background.
- <code>wb_localization_dataset_set2</code>: The dataset after applying data augmentation on images containing small characters.
- <code>wb_localization_dataset_set3</code>: The dataset after applying data augmentation on images containing yī characters.
- <code>wb_localization_dataset_set4</code>: The dataset after applying data augmentation on stained images.
- <code>wb_localization_dataset_all</code>: The combination of four separated augmentation dataset above.
- <code>wb_localization_dataset_more</code>: The dataset after applying data augmentation on images containing oversized characters.
- <code>test_dataset</code>: Images from NomFoundation website for model testing purpose.

