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
    num_bytes: 6274726
    num_examples: 3335
  - name: validation
    num_bytes: 705888
    num_examples: 371
  download_size: 6986028
  dataset_size: 6980614
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: validation
    path: data/validation-*
---
