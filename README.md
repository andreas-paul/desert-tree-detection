# Detection of desert trees on satellite imagery

[ WORK IN PROGRESS ] 

This project showcases an end-to-end deep learning system to detect trees on satellite imagery.

- Features to be implemented:
  - DeepForest: https://github.com/weecology/DeepForest
  - DETR: https://huggingface.co/docs/transformers/en/model_doc/detr
  - Tessera embeddings: https://github.com/ucam-eo/tessera

- No installation is needed, only Docker must be installed. All required data is either part of the package or will be downloaded when the application is running.

- It is best run on a somewhat powerful machine such as a gaming laptop or workstation.

### Area
<img width="1201" height="735" alt="uae-forest-01_overview" src="https://github.com/user-attachments/assets/0a16657c-30bb-400e-86cf-da531da3c9b9" />

### Training
- Manual labels were placed in QGIS and export as geojson:
<img width="3423" height="1914" alt="uae-trees_labels" src="https://github.com/user-attachments/assets/eee6ba43-aca5-4aae-b7d7-1ce4410bff52" />

### Initial Results
#### DeepForest
Below the initial results of using the DeepForest model to predict trees on satellite imagery without any additional labels - only very few of the trees were detected, namely those that show high structural detail compared to the surrounding specimen. Note that DeepForest is created for drone imagery with much higher GSD compared to the satellite image.

<img width="497" height="307" alt="uae-forest-01_sub02_prediction-01" src="https://github.com/user-attachments/assets/28b94089-b803-419f-b3ed-979da1f275a1" />
