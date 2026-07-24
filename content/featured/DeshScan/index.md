---
date: '2025-07-02'
title: 'DeshScan — Private On-Device Document Scanner'
cover: './demo.png'
github: 'https://github.com/munawaransary/deshscan'
external: ''
tech:
  - Python
  - PyTorch
  - U-Net
  - OpenCV
  - OCR
---

A free, private document scanner where your documents never leave your device. Photograph any document — NID card, certificate, form — and get a clean, flattened, shareable scan. A compact U-Net, trained on self-generated synthetic shadow pairs, removes shadows and color casts, and the whole pipeline (detect → dewarp → shadow removal → OCR → PDF) runs locally, even on CPU. Supports Bangla + English OCR.
