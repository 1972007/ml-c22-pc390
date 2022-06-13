# ml-c22-pc390
A collection of collab file to keep track of the model's progress<br/>

File C22-PC390 belongs to Joseph<br />
File Copy of dermapp belongs to Salsabila Audrey<br />

This colab contains :
* The dataset extraction, loading, and augmentation. (Varies per dataset)
* Models that is made with, and without transfer learning
* Testing

Note :
variables containing file path should be changed as needed. It's a path from the owner's environment<br />

Extraction and Loading :
For HAM10000 dataset [1,2], there are 2 folders containing the training set and 1 folders containing the validation set<br />
For other dataset taken from Kaggle (dermapp or skin-disease-dataset or skin-disease-image-dataset), it's already ordered properly.<br />


The data was then loaded into a ImageDataGenerator with nessecary augment and splitting.

Model :
There are various model that was tried. The one noteworthy are the Model from Scratch and Model from Xception transfer learning.

Test:
If at ImageDataGenerator, the test generator is made, the model can be evaluated by the generator.

Citation : 
[1] Noel Codella, Veronica Rotemberg, Philipp Tschandl, M. Emre Celebi, Stephen Dusza, David Gutman, Brian Helba, Aadi Kalloo, Konstantinos Liopyris, Michael Marchetti, Harald Kittler, Allan Halpern: "Skin Lesion Analysis Toward Melanoma Detection 2018: A Challenge Hosted by the International Skin Imaging Collaboration (ISIC)", 2018; https://arxiv.org/abs/1902.03368<br />

[2] Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).
