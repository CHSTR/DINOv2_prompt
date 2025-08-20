# DINOv2 adaptation with Prompt Learning

<p align="center">
  <img src="https://github.com/user-attachments/assets/b4a20f9d-ff75-411d-9284-08e613e515c6" width="45%" />
  <img src="https://github.com/user-attachments/assets/5dfc827c-defe-4d3c-ab56-d7d9e1565c35" width="45%" />
</p>

## Dependencies

On the basis of `Python >= 3.9` environment, install the necessary dependencies by running the following command:

```shell
pip install -r requirements.txt
```

## Inference Example
Example of how to use the `s3bir encoder`. Make sure you have downloaded the [model](https://drive.google.com/drive/folders/1n6Z2iNKFQLWLAFu7j9Ra2m0ixKfkobgo?usp=sharing) before running the script.

When working with images, the forward pass must receive the argument `dtype='image'`, and for sketches, use `dtype='sketch'`.

```shell
python3 s3bir_encoder.py
```

Demo on [huggingface](https://chstr-s3bir.hf.space/)