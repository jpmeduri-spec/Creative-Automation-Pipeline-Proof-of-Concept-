# Creative Automation Pipeline (Proof of Concept)

## Overview
This repo demonstrates a **creative automation pipeline** for localized social ad campaigns using GenAI.  
It accepts campaign briefs, reuses existing assets, generates missing creatives, and outputs ad-ready images in multiple aspect ratios.

## Features
- Accepts campaign briefs in JSON format
- Uses existing assets when available
- Generates missing assets via GenAI (mocked in PoC)
- Produces creatives in 1:1, 9:16, 16:9 ratios
- Overlays campaign message
- Saves organized outputs by product and ratio

## Requirements
- Python 3.8+
- Pillow (`pip install pillow`)

## Usage
```bash
python pipeline.py
