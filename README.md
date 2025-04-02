# DNAGAST

The official code repository for the DNAGAST model.

## Dependencies

- [LMDBM (modified)](https://github.com/SirDavidLudwig/lmdb-python-dbm)
- [Tensorflow](https://www.tensorflow.org/)
- [tf-utils](https://github.com/DLii-Research/tf-utils)
- [tf-set-transformer](https://github.com/DLii-Research/tf-set-transformer)
- [Weights & Biases](https://wandb.ai)

## Training & Evaluation

Each model architecture can me trained/evaluated by invoking the appropriate script located in the `scripts/` directory. These scripts integrate the Weights & Biases platform directly for easy version control, thus W&B must be configured appropriately on your system before execution.
