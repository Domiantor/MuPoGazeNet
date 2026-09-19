# MuPo-GazeNet

Companion repository for the manuscript:

**One-second calibrated head-pose-guided eye tracking for unconstrained AR eyewear**

## Overview

MuPo-GazeNet is a multimodal gaze-estimation framework for head-mounted augmented reality eyewear. It integrates near-eye images and head-pose sequences through a Transformer-based architecture to model head–eye coordination.

A lightweight bias-compensation module enables personalized gaze estimation with approximately one second of single-point calibration, without retraining the backbone network.

![Overview of MuPo-GazeNet](assets/overview.png)

*Overview of the challenges, proposed framework, and potential applications of MuPo-GazeNet.*

## Dataset Examples

Representative dataset samples will be added to the [`dataset_examples/`](dataset_examples/) folder for browsing.

## Reported Results

The manuscript reports:

- **Offline evaluation:** mean angular error of 1.32°.
- **Real-device evaluation:** mean angular error of 1.74°.
- **Inference latency:** 48.6 ms per frame on the reported evaluation platform.
- **Calibration time:** approximately 1 second.
