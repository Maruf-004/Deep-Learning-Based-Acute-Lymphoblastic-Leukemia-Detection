# Deep-Learning-Based-Acute-Lymphoblastic-Leukemia-Detection

Acute Lymphoblastic Leukemia (ALL) is a prevalent and potentially fatal blood-related cancer
that primarily affects individuals, including children and adults. For better patient outcomes
and surgical therapy, early detection and precise subtyping are essential. Conventional diagnosis methods are intricate and time-consuming, which increases the risk of human error and
delays in receiving therapy. Our aim in this study is to establish a deep learning-based system
to diagnose ALL from bone marrow smear images without the help of any manual interpretations. This research introduces an effective bone marrow smear image preprocessing technique,
optimizing these images for subsequent input into convolutional neural networks, ultimately
enhancing the diagnostic accuracy and efficiency of ALL detection. The models used in this
study show outstanding performances by using this preprocessing technique. With a stunning
99.69% accuracy in ALL identification, Resnet152v2ALL outperforms the previously released
best model VGG19 (98.50%) by a substantial margin. This better-than-expected performance demonstrates the value of our suggested model design, data augmentation techniques,
and interpretability analysis.By presenting a very precise and intelligible deep learning model,
this thesis improves the area of computerized ALL diagnosis in bone marrow smears. The clinical use of Resnet152v2ALL shows great promise for accelerating and improving ALL patient
care through faster and more accurate diagnostics.

Dataset: The images of this dataset were prepared in the bone marrow laboratory of Taleqani Hospital (Tehran, Iran). This dataset consisted of 3256 PBS images from 89 suspected of ALL patients whose blood samples were prepared and stained by skillful laboratory staff. This dataset is divided into two classes benign and malignant. The former comprises hematogones; the latter is the ALL group with three subtypes of malignant lymphoblasts: Early Pre-B, Pre-B, and Pro-B ALL. All the images were taken using a Zeiss camera in a microscope with 100x magnification and saved as JPG files. A specialist using the flow cytometry tool made the definitive determination of the types and subtypes of these cells. After color thresholding-based segmentation in the HSV color space, we also provide segmented images.
https://www.kaggle.com/datasets/mehradaria/leukemia
