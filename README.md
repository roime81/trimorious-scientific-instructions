---
dataset_info:
  features:
  - name: messages
    list:
    - name: role
      dtype: string
    - name: content
      dtype: string
  splits:
  - name: train
    num_bytes: 6019
    num_examples: 5
  - name: validation
    num_bytes: 1221
    num_examples: 1
  download_size: 13733
  dataset_size: 7240
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: validation
    path: data/validation-*
---
