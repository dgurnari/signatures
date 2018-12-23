# signatures
repository for the CBSD 18/19 signature verification project 

the datasets can be found at https://www.math.unipd.it/~nnavarin/Projects/

all the code shoud be compliant with the original folder strucure of the datasets


Execution time: 

- Without preprocession,  hog(img_resized,orientations=11, pixels_per_cell=(4,4), cells_per_block=(2,2), block_norm='L2-Hys')

                 precision    recall  f1-score   support

Genuine Forgery       0.66      0.64      0.65       235
Genuine Genuine       0.66      0.68      0.67       239

    avg / total       0.66      0.66      0.66       474

Uptime : 0:35:21.516045


- Without preprocession, hog(image, orientations=8,pixels_per_cell=(4, 4),cells_per_block=(2, 2),block_norm='L2-Hys')

                 precision    recall  f1-score   support

Genuine Forgery       0.70      0.68      0.69       235
Genuine Genuine       0.69      0.71      0.70       239

    avg / total       0.70      0.70      0.70       474

Uptime : 0:25:33.255028

- PREPROCESSING (binarization, hog(image, orientations=8,pixels_per_cell=(4, 4),cells_per_block=(2, 2),block_norm='L2-Hys') AND bigger images (100 x 150)

precision    recall  f1-score   support

Genuine Forgery       0.72      0.69      0.71       235
Genuine Genuine       0.71      0.74      0.72       239

    avg / total       0.72      0.72      0.72       474

Uptime : 0:51:21.900927
