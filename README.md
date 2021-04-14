# Mogrifier LSTM 

## Data Set
Data set dapat diambil dari link berikut
[Dataset](https://github.com/duump/dsc/blob/main/brown.txt)

## Instalation
*  Clone Repo
`https://github.com/duump/dsc/`

* Rubah ke directory Clone Repo
`cd dsc`

*  Instalation Requritment
`pip install -r requirements.txt`

## Hasil Pengujian
## Model LSTM

* Link Google Colab untuk 10K Dataset [10K](https://colab.research.google.com/drive/1hWramWZkPAu1xJd7QbiYM0W8WSgMH1PT?usp=sharing)
* Link Google Colab untuk 15K Dataset [15K](https://colab.research.google.com/drive/1v3o-eShGoT11biy0McY1bP2_EDbLnOu8?usp=sharing)
* Link Google Colab untuk 20K Dataset [20K](https://colab.research.google.com/drive/16B0MJNSsSt7A4rW1o8O6jx47e0h-Ol3c?usp=sharing)

| Model           | Dataset   | Epoch            |  Best Epoch           |  Validation Loss |
| --------------- | ---------  | ---------------- | --------------------- | ---------------- |
| LSTM PYTORCH    | 10K         | 209              |  207                  |  1,57801574      |
| LSTM Standard| 10K          | 209              |  209                  |  1,5641779      |
| LSTM MORGIFIER| 10K          | 149              |  143                  |  1,54823017   |
| LSTM PYTORCH    | 15K          | 209              |  209                  |  1,49400002      |
| LSTM Standard| 15K         | 209              |  209                  |  1,48335578      |
| LSTM MORGIFIER| 15K         | 122              |  116                  |  1,47629633   |
| LSTM PYTORCH    | 20K          | 209              |  209                  |  1,51462121      ​|
| LSTM Standard| 20K        | 209              |  209                  |  1,50521718      ​|
| LSTM MORGIFIER| 20K          | 138              |  132                  |  1,50269374 ​|







### LSTM PYTORCH
`{'best_epoch': 207, 'best_validation_loss': 1.5780157446861267, 'epoch': 209, 'peak_cpu_memory_MB': 3366.832, 'peak_gpu_0_memory_MB': 1170, 'training_cpu_memory_MB': 3366.832, 'training_duration': '00:48:36', 'training_epochs': 209, 'training_gpu_0_memory_MB': 1170, 'training_loss': 1.490157127380371, 'training_start_epoch': 0, 'validation_loss': 1.5780253112316132}
`

### LSTM Standard
`{'best_epoch': 209, 'best_validation_loss': 1.5641779899597168, 'epoch': 209, 'peak_cpu_memory_MB': 3373.536, 'peak_gpu_0_memory_MB': 1234, 'training_cpu_memory_MB': 3373.536, 'training_duration': '00:06:02', 'training_epochs': 209, 'training_gpu_0_memory_MB': 1234, 'training_loss': 1.4667911721814064, 'training_start_epoch': 0, 'validation_loss': 1.5641779899597168}
`


### LSTM Mogrifier

`{'best_epoch': 143, 'best_validation_loss': 1.5482301712036133, 'epoch': 149, 'peak_cpu_memory_MB': 3393.124, 'peak_gpu_0_memory_MB': 1304, 'training_cpu_memory_MB': 3393.124, 'training_duration': '00:57:52', 'training_epochs': 149, 'training_gpu_0_memory_MB': 1304, 'training_loss': 1.4016051253964823, 'training_start_epoch': 0, 'validation_loss': 1.5496252477169037}
`
