tahap penggunaan algoritma:

- pertama, running Classification_CNN_Default.ipynb untuk mendapatkan hasil performansi CNN dengan parameter default.

- selanjutnya, urutan untuk tuning hyperparameter algoritma CNN yaitu running Classification_epoch_CNN.ipynb, lalu Classification_learning rate_CNN.ipynb, Classification_batch size_CNN.ipynb, dan terakhir, Classification_optimizer_CNN.ipynb.

- hasil terbaik dapat dilihat pada performansi Classification_optimizer_CNN.ipynb yang tertinggi.


Algoritma CNN Klasifikasi terbaik dengan parameter

epochs=100
batch_size=128
learning rate 0,0001
optimizer RMS dengan hasil akurasi 98.70664477348328%

Best results obtained in fold 3: Adam

Accuracy: 98.11875224113464%

Loss: 0.07862861454486847

specificity: 99.0740716457367

Sensitivity: 97.24979446848776

Best results obtained in fold 4: SGD

Accuracy: 97.00176119804382%

Loss: 1.321115493774414

specificity: 98.55324029922485

Sensitivity: 93.22135486250708

Best results obtained in fold 3: RMSprop

Accuracy: 98.70664477348328%

Loss: 0.06255502998828888

specificity: 99.3634283542633

Sensitivity: 98.2857779629259
