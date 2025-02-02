# DeepEdit for Lung Segmentation

### Model Overview

Interactive MONAI Label App using DeepEdit to label lungs over CT Images

### Data

The training data is from Kaggle (https://www.kaggle.com/andrewmvd/covid19-ct-scans).


The script **convert_to_single_label.py** could be used to convert images from multiple label into single label


- Target: Lungs
- Task: Segmentation 
- Modality: CT

### Inputs

- 1 channel CT
- 3 channels (CT + foreground points + background points)

### Output

- 1 channel representing lungs


![DeepEdit for lungs](../docs/images/sample-apps/deepedit_lungs.png)
