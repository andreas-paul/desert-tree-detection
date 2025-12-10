# Detection of desert trees on satellite imagery

[ WORK IN PROGRESS ] 

This project showcases an end-to-end deep learning system to detect trees on satellite imagery.

Features:
- Two algorithms implemented:
  - DeepForest: https://github.com/weecology/DeepForest
  - DETR: https://huggingface.co/docs/transformers/en/model_doc/detr

- No installation is needed, only Docker must be installed. All required data is either part of the package or will be downloaded when the application is running.
- It is best run on a somewhat powerful machine such as a gaming laptop or workstation.

- Manual labels were placed in QGIS and export as geojson:
<img width="3423" height="1914" alt="uae-trees_labels" src="https://github.com/user-attachments/assets/eee6ba43-aca5-4aae-b7d7-1ce4410bff52" />
