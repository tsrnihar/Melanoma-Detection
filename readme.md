Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

Project Pipeline:
- Data Reading/Data Understanding
- Dataset Creation: Creating Train/Validation datasets
- Dataset visualisation: Visualizing one image per class
- Model building and training
	- Addressing Overfitting
	- Addressing low accurachy
	- Addressing class imbalance
- Rerunning the model after making the above changes
- Visualizing the validation loss and accuracy
