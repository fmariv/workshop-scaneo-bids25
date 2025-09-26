# Training AI models with SCANEO for intelligent satellite image labeling: a hands-on tutorial

This tutorial is designed to guide participants through the end-to-end process of training AI models using SCANEO, a state-of-the-art, AI-powered labeling tool specifically designed for satellite imagery.

SCANEO uses active learning to significantly accelerate and improve the accuracy of the data labeling process, which is typically a bottleneck when working with large volumes of Earth Observation (EO) data. Participants will learn how to leverage SCANEO to generate high-quality labeled datasets for training deep learning models, particularly in the context of satellite image analysis.

Participants will gain hands-on experience with SCANEO, starting from selecting areas of interest in satellite imagery to generating labeled datasets for tasks like semantic segmentation and object detection. Thanks to its active learning loop, SCANEO allows participants to iteratively improve model performance by minimizing labeling errors and efficiently labeling large datasets.

In addition to SCANEO, we will briefly cover how to integrate these labeled datasets into the Earth Observation Training Data Lab (EOTDL) or storage, management, and collaborative use.

## Agenda

This tutorial will be heavily based on the SCANEO graphical interface, so there are few notebooks:

1. [SCANEO](01_scaneo.ipynb)
2. [How to contribute](02_contributing.ipynb)

## Getting Started

You can follow the tutorial in two ways:

- Watch the live demonstration and run the notebooks later at your own pace.

- Follow along interactively on your own machine:

  - Clone this repository:

    `git clone https://github.com/fmariv/workshop-scaneo-bids25.git`

    - Install Python (minimum version 3.12) and create a virtual environment using [uv](https://docs.astral.sh/uv/). If you don't have `uv` installed, you can follow the instructions [here](https://docs.astral.sh/uv/getting-started/installation/)

    - Synchronize the environment:

      `uv sync`

    - Open the notebook in Visual Studio Code or your preferred IDE.

Any questions? Let’s get started with the notebook!

## Community

We invite you to join our Discord server to ask questions, connect with other participants, and receive updates about the SCANEO project even after the event.

<div style="text-align: center;"> <img src="images/discord-qr.png" width=350> </div>

Scan the QR code to join our Discord channel!

## Additional Resources

- [SCANEO GitHub](https://github.com/earthpulse/scaneo)
- [SCANEO service in the EOTDL HUB](https://hub.api.eotdl.com/services/eoxhub-gateway/eotdl/scaneo/)
