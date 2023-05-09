# Faster-RCNN
[TORCHVISION OBJECT DETECTION FINETUNING TUTORIAL ](https://pytorch.org/tutorials/intermediate/torchvision_tutorial.html)

The colab notebook wouldn't run locally on my mac.

Made some changes so it works.

Notes:

- may need to install `wget` via homebrew
- Seemingly doesn't take advantage of mps or parallel processing:
  - ```[W MPSFallback.mm:13] Warning: The operator 'torchvision::nms' is not currently supported on the MPS backend and will fall back to run on the CPU. This may have performance implications. (function operator())```
  - Support is tracked @ [pytorch issue #77764](https://github.com/pytorch/pytorch/issues/77764)
