# tiny-language-model documentation!

## Description

Ever wondered how small you can make a LLM? Look no further, you have found the smol brain model.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `gsutil rsync` to recursively sync files in `data/` up to `gs://generic-dataset/data/`.
* `make sync_data_down` will use `gsutil rsync` to recursively sync files in `gs://generic-dataset/data/` to `data/`.


