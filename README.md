# SVG to Turtle Graphics Converter

## Overview
This script transforms Scalable Vector Graphics (SVG) files into commands for Turtle graphics. Turtle graphics is a beginner-friendly method for creating visual patterns and shapes using a virtual turtle.

The script takes an SVG file, extracts its path details, and converts these into Turtle graphics commands. This allows for the rich visuals of SVG files to be recreated with the Turtle graphics system.

## Features
+ Converts SVG to Turtle graphics commands.
+ Handles SVG path commands like M, L, C, and Z.
+ Adjusts SVG coordinates to fit the Turtle graphics space.
+ Preserves the original SVG colors and strokes in Turtle format.
+ Compatible with common Turtle graphics libraries.

## Install dependencies

```
git clone https://github.com/lucthienphong1120/SVG-Turtle-Converter.git
cd SVG-Turtle-Converter
pip install -r requirements.txt
```

## Usage
1. Vectorize an image to SVG file: https://vectorizer.ai.
2. To convert an SVG file to Turtle draw

```
python turtle-svg.py -s input.svg
```

![Sample](./output.png)