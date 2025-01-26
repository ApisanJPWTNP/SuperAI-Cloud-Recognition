# Sky Condition Classification Project

This project involves classifying sky conditions from images, with seven distinct categories of cloud formations and weather conditions:

1. **Cirroform Clouds**
2. **High Cumuliform Clouds**
3. **Stratocumulus Clouds**
4. **Cumulus Clouds**
5. **Cumulonimbus Clouds**
6. **Stratiform Clouds**
7. **Clear Sky**

## Dataset Overview

- **Training Set**: 960 images
  - **Class 0 (Cirroform Clouds)**: 143 images
  - **Class 1 (High Cumuliform Clouds)**: 236 images
  - **Class 2 (Stratocumulus Clouds)**: 132 images
  - **Class 3 (Cumulus Clouds)**: 211 images
  - **Class 4 (Cumulonimbus Clouds)**: 25 images
  - **Class 5 (Stratiform Clouds)**: 89 images
  - **Class 6 (Clear Sky)**: 124 images

- **Test Set**: 700 images

## File Descriptions

- **train.csv**: The training set containing image information and corresponding labels.
- **test.csv**: The test set used for making predictions.
- **submit.csv**: A sample submission file in the correct format.

## Data Fields

- **id**: The image name.
- **label**: The label associated with the image, representing the sky condition.
- **predict**: The predicted label for the image (used in the submission file).

## Usage

1. **Training**: Train your model using the `train.csv` dataset.
2. **Prediction**: Make predictions on the test images and submit your results in the `submit.csv` file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

