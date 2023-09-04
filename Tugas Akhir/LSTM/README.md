tahap penggunaan algoritma:

- pertama, running Classification_LSTM_Default.ipynb untuk mendapatkan hasil performansi LSTM dengan parameter default.

- selanjutnya, urutan untuk tuning hyperparameter algoritma LSTM yaitu running Classification_epoch_LSTM.ipynb, lalu Classification_learning rate_LSTM.ipynb, Classification_batch size_LSTM.ipynb, dan terakhir, Classification_optimizer_LSTM.ipynb.

hasil terbaik dapat dilihat pada performansi Classification_optimizer_LSTM.ipynb yang tertinggi.

Algoritma LSTM Klasifikasi terbaik dengan parameter

epochs=100
batch_size=64
learning rate 0,001
optimizer RMS dengan hasil akurasi 98.47148656845093%
Best results obtained in fold 5: Adam

Accuracy: 97.7647066116333%

Loss: 0.04258622229099274

specificity: 98.92939925193787

Sensitivity: 96.38755231614611

Best results obtained in fold 5: SGD

Accuracy: 93.76470446586609%

Loss: 0.12929394841194153

specificity: 96.58564925193787

Sensitivity: 87.20415429319539

Best results obtained in fold 3: RMSprop

Accuracy: 98.47148656845093%

Loss: 0.03478509187698364

specificity: 99.24768805503845

Sensitivity: 97.6741030671589
