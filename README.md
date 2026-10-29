# ChaiPhoto model assets

This repository distributes model files for the opt-in developer model laboratory in ChaiPhoto. It contains no application source code or user photos. Images are processed locally on the device.

## Source and license

The image and text encoders are converted from OFA-Sys Chinese-CLIP RN50, whose official model card identifies the weights as Apache-2.0.

- Original model: https://huggingface.co/OFA-Sys/chinese-clip-rn50
- Official implementation and conversion utilities: https://github.com/OFA-Sys/Chinese-CLIP
- Paper: https://arxiv.org/abs/2211.01335

Changes: conversion to Core ML neural-network format and FP16 weight compression. The image and text encoders remain a paired model. Downloads must be checked against the manifest SHA-256 hashes before compilation. These are experimental retrieval models; similarity scores are not calibrated probabilities.

All distributions include the applicable model license. No Apple MobileCLIP weights are included.
