# A Study On The Segment Anything Model By Meta AI

Original paper: https://arxiv.org/pdf/2304.02643v1.pdf
Original GitHub: https://github.com/facebookresearch/segment-anything
Website: https://segment-anything.com/

Install necessary libraries by running the following two lines:

```
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install opencv-python pycocotools matplotlib onnxruntime onnx
```

# Find pre-trained weights at:

Click the links below to download the checkpoint for the corresponding model name and place it in the root directory.

* **`default` or `vit_h`: [ViT-H SAM model.](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth)**
* `vit_l`: [ViT-L SAM model.](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_l_0b3195.pth)
* `vit_b`: [ViT-B SAM model.](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth)

# To-do

- [x] Go over research paper and create a summary ([SAM Research Paper Summary](https://github.com/PragyanSubedi/Segment-Anything-Model-Breakdown/blob/main/SAM%20Research%20Paper%20Summary.ipynb))
- [ ] Interpret the segment_anything library