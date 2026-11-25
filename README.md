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
    num_bytes: 6274634
    num_examples: 3335
  - name: validation
    num_bytes: 705888
    num_examples: 371
  download_size: 6985936
  dataset_size: 6980522
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: validation
    path: data/validation-*
---
