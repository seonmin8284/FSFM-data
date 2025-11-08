# FSFM Test Data

Custom-generated test data for FSFM (Face Security Foundation Model) deepfake detection project.

## Contents

This repository contains AI-generated images and videos for testing deepfake detection models:

### ComfyUI Generated Images (5 files, 9.5MB)
- `ComfyUI_00017_.png` - 1.5MB
- `ComfyUI_00018_.png` - 177KB
- `ComfyUI_00019_.png` - 445KB
- `ComfyUI_00020_.png` - 393KB
- `ComfyUI_00021_.png` - 7.1MB

### AnimateDiff Generated Videos & Images (10 files, 21.5MB)
- `AnimateDiff_00001.mp4` - 1.9MB + PNG thumbnail 535KB
- `AnimateDiff_00002.mp4` - 2.0MB + PNG thumbnail 749KB
- `AnimateDiff_00003.mp4` - 1.7MB + PNG thumbnail 532KB
- `AnimateDiff_00004.mp4` - 7.6MB + PNG thumbnail 1.5MB
- `AnimateDiff_00005.mp4` - 3.4MB + PNG thumbnail 1.6MB

**Total Size**: ~31MB (15 files)

## Generation Tools

- **ComfyUI**: Stable Diffusion based image generation
- **AnimateDiff**: Motion module for video generation

## Purpose

These files are used for testing the FSFM deepfake detection model's inference pipeline, including:
- Face detection (Mediapipe + Haar Cascade)
- Frame extraction from videos
- ViT-based classification

## License

These are custom-generated synthetic data for research and testing purposes.

## Related Project

Main project: [FSFM](https://github.com/wavico/FSFM)
