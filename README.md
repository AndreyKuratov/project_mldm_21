# project_mldm_21

Проект по курсу [MLDM'21](https://github.com/HSE-LAMBDA/MLDM-2021/blob/main/Exam-project-guidelines.md). Название проекта: [Rainforest Connection Species Audio Detection](https://www.kaggle.com/c/rfcx-species-audio-detection/overview)


---
## Результаты для единичной модели

| Название файла| LRAP priv./pub. | дата| комментарий|
| ------------- | ------------- | ------------- |------------- |
|  model_Res18_epoch_30_level_1| 0.51522/0.52114 | 27.01.22 |Простая модель, неаугментированные данные, мало эпох, проверка работоспособности|
|  model_Res18_epoch_20_level_1plusLR1e2| 0.52393/0.50836 | 28.01.22 |Простая модель, аугментация картинок, мало эпох|
|  model_Res50pt_epoch_100_level_tpfpshiht4k| 0.53493/0.53297 | 29.01.22 | Предобученная модель Resnet50, аугментация сдвига, изменяющаяся LR |
| model_Res18_audaud_ShG_bG.csv | 0.56613/0.54598 | 31.01.22|Предобученная модель Resnet18, аугментация аудио файлов, gauss,shift |
| model_Res18_augTotal.csv | 0.59104/0.58790 | 31.01.22| Предобученная модель Resnet18, большая аугментация аудио файлов, gauss,shift |
| model_short_slices (Res50) |0.76910/0.76390| 31.01.22| Предобученная модель Resnet50, аугментация вырезания из спектрограммы|
| --.csv | -/- | --.--.22|--|

## Результаты для групп моделей
| Название файла| LRAP priv./pub. | дата| комментарий|
| ------------- | ------------- | ------------- |------------- |
| model_epoch_100_stack_model_3models.csv | 0.529/0.527 | 01.02.22|--|
| model_epoch_100_stack_model_2models.csv | 0.596/0.592 | 01.02.22|--|
| --.csv | -/- | --.--.22|--|

---
## Полезные ссылки
#### Kaggle
| Название/ссылка|комментария |
| ------------- | ------------- |
|[Introduction to Sound Event Detection](https://www.kaggle.com/hidehisaarai1213/introduction-to-sound-event-detection)||
|[Sound Classification using Spectrogram Images](https://www.kaggle.com/devilsknight/sound-classification-using-spectrogram-images)||
|[Birdcall Recognition: EDA and Audio FE](https://www.kaggle.com/andradaolteanu/birdcall-recognition-eda-and-audio-fe)||
|[Explore the Rainforest Soundscape](https://www.kaggle.com/gpreda/explore-the-rainforest-soundscape)||
|[Beginner's Guide to Audio Data](https://www.kaggle.com/fizzbuzz/beginner-s-guide-to-audio-data)||
|[Respiratory Sound Classification](https://www.kaggle.com/georgekantasis/respiratory-sound-classification)||
|[Sound Classifier Introduction](https://www.kaggle.com/aditya48/sound-classifier-introduction)||
|[Sound Classifier Introduction](https://www.kaggle.com/aditya48/sound-classifier-introduction)||
|[Introduction to Sound Analysis](https://www.kaggle.com/mrhippo/introduction-to-sound-analysis)||
|[In-depth introduction to audio for beginners](https://www.kaggle.com/deepaksinghrawat/in-depth-introduction-to-audio-for-beginners)||
|[Topic 9. Part 1. Time series analysis in Python](https://www.kaggle.com/kashnitsky/topic-9-part-1-time-series-analysis-in-python)||
|[Topic 9. Part 2. Time series with Facebook Prophet](https://www.kaggle.com/kashnitsky/topic-9-part-2-time-series-with-facebook-prophet)||


#### GitHub SED (SoundEventDetection)
| Название/ссылка|комментария |
| ------------- | ------------- |
|[Visualization toolbox for SED](https://github.com/TUT-ARG/sed_vis)||
|[GitHub ыуфкср](https://github.com/search?q=sound+event+detection)||
[]()

#### Other
| Название/ссылка|комментария |
| ------------- | ------------- |
|[Open Machine Learning Course](https://mlcourse.ai/)||
|[paperswithcode: Sound Event Detection (SED)](https://paperswithcode.com/task/sound-event-detection)||
|[Sound Event Detection: A Tutorial (Arxiv)](https://arxiv.org/abs/2107.05463)||
[]()


## Полезные блокноты
#### Explore and ...
| Название/ссылка|комментария |
| ------------- | ------------- |
|[Explore](https://www.kaggle.com/gpreda/explore-the-rainforest-soundscape)||
|[Create Image Dataset with W&B](https://www.kaggle.com/ayuraj/rainforest-create-image-dataset-with-w-b)|STFT, MFCC based sptgrm, Log(sptgrm)|
|[use librosa](https://www.kaggle.com/hamditarek/rainforest-connection-analysis-using-librosa)||
|[feature-extraction](https://www.kaggle.com/shreyasajal/birdclef-2021-librosa-audio-feature-extraction)||
|[spectrogram](https://www.kaggle.com/theoviel/spectrogram-generation)||
|[adversarial](https://www.kaggle.com/tunguz/adversarial-rainforest)||
|[pytorch-stater](https://www.kaggle.com/gopidurgaprasad/rfcs-audio-detection-pytorch-stater)||
|[post-process](https://www.kaggle.com/cdeotte/rainforest-post-process-lb-0-970)||
|[baseline-for-beginners](https://www.kaggle.com/fffrrt/all-in-one-rfcx-baseline-for-beginners)||
|[]()||

#### Augmentation
| Название/ссылка|комментария |
| ------------- | ------------- |
|[RFCX: Audio Data Augmentation](https://www.kaggle.com/hidehisaarai1213/rfcx-audio-data-augmentation-japanese-english)||
|[Augmentation](https://www.kaggle.com/duythanhng/rfcx-torchvision-models-augmentation)||
|[Augmentation](https://www.kaggle.com/gopidurgaprasad/audio-augmentation-albumentations)||
|[SolSet](https://www.kaggle.com/mehrankazeminia/automl-inference-audio-detection-soliset)||
|[]()||
|[]()||
|[]()||

#### Models
| Название/ссылка|комментария |
| ------------- | ------------- |
|[RFCX: train resnet50](https://www.kaggle.com/yosshi999/rfcx-train-resnet50-with-tpu)||
|[resnet34](https://www.kaggle.com/khoongweihao/resnet34-more-augmentations-mixup-tta-inference)||
|[pytorch-lightning](https://www.kaggle.com/jackvial/pytorch-lightning-starter) ||
|[xgboost fft cuml](https://www.kaggle.com/titericz/0-525-tabular-xgboost-gpu-fft-gpu-cuml-fast)||
|[Bagging](https://www.kaggle.com/saurabhbagchi/rfcx-bagging-with-different-weights-0-879-score)||
|[resnet wavenet ensemble](https://www.kaggle.com/aikhmelnytskyy/resnet-wavenet-my-best-single-model-ensemble)||
|[Mean Teachers](https://www.kaggle.com/reppic/mean-teachers-find-more-birds)||
|[LogisticRegression](https://www.kaggle.com/titericz/0-309-baseline-logisticregression-using-fft)||
|[resnet](https://www.kaggle.com/meaninglesslives/rfcx-minimal)||
|[h](https://www.kaggle.com/kneroma/inference-tpu-rfcx-audio-detection-fast)||
|[ResNet](https://www.kaggle.com/kneroma/inference-resnest-rfcx-audio-detection)||
|[ResNet](https://www.kaggle.com/aikhmelnytskyy/resnet-tpu-on-colab-and-kaggle)||
|[]()||
|[]()||
|[]()||
|[]()||
|[]()||

