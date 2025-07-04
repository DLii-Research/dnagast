# [DNAGAST]()

The official code repository for [DNAGAST: Generative Adversarial Set Transformers for High-throughput Sequencing]().

## Dependencies

- [LMDBM (modified)](https://github.com/SirDavidLudwig/lmdb-python-dbm)
- [Tensorflow](https://www.tensorflow.org/)
- [tf-utils](https://github.com/DLii-Research/tf-utils)
- [tf-set-transformer](https://github.com/DLii-Research/tf-set-transformer)
- [Weights & Biases](https://wandb.ai)

## Training & Evaluation

Each model architecture can be trained and evaluated by invoking the appropriate script located in the `scripts/` directory. These scripts integrate the Weights & Biases platform directly for version control, thus W&B must be configured appropriately on your system before execution.

## Citation

```
@article{ludwig_dnagast_2025,
    title={DNAGAST: Generative Adversarial Set Transformers for High-throughput Sequencing},
    author={Ludwig II, David W. and Phillips, Joshua L.},
    journal={The International FLAIRS Conference Proceedings},
    volume={38},
    issn = {2334-0762},
    year={2025},
    month={May}
}
```
