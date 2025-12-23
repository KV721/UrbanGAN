# UrbanGAN: AI-Assisted Urban Block Design Generation

## Overview
This project implements a Generative Adversarial Network (GAN) framework to automate urban block design. Using a **Pix2Pix** conditional GAN architecture, the model learns to generate realistic building footprints and urban layouts based on road network inputs.

## Key Features
* **Architecture:** Utilizes a Pix2Pix conditional GAN with an encoder-decoder generator and PatchGAN discriminator.
* **Dataset:** Trained on a custom dataset of **2,000 images** derived from **50 cities** (including Milan, Amsterdam, and Bengaluru) to capture diverse urban morphologies.
* **Data Pipeline:** Automated extraction of road networks and building footprints using **OpenStreetMap (OSM)** and **OSMnx**.
* **Tech Stack:** Python, PyTorch/TensorFlow, OSMnx, QGIS.

## Objective
The goal is to overcome the limitations of rule-based urban planning by allowing AI to learn complex spatial dependencies directly from real-world data, enabling the generation of adaptable and sustainable urban designs.
