# Dutch Flood Policy Optimization (IJssel River) - Overijssel's Perspective

This repository contains the final assignment for TU Delft's EPA141A course, focusing on flood policy optimization for the IJssel River in Overijssel. The project leverages the Multi-Scenario Multi-Objective Robust Decision Making (MORDM) framework to analyze and optimize flood management strategies under deep uncertainty.

**Credit:** This project builds upon the original model available at [https://github.com/quaquel/epa141A_open](https://github.com/quaquel/epa141A_open).

**Authors:**
* Myriam Kammüller Pont
* Rachel Delvin Sutiono
* Thunchanok Phutthaphaiboon
* Yao Wang

## Key Components

Here is a simple overview of what you will find in this repository. Each part matches a jupyter notebook that helps with a different step in optimizing flood policies for the IJssel River.

- **00 Policy Simulation Tool**: Simulates flood management policies and their impacts using the dike model.
- **01 Scenario Analysis**: Explores different future scenarios and select 4 intereting/vulnerable scenarios to perform policy search.
- **02 Direct Search**: Optimizes policy choices through direct search algorithms.
- **03 Robustness Evaluation**: Evaluates how robust policies are across a range of scenarios.
- **04 Scenario Discovery**: Identifies critical scenarios and tipping points affecting policy outcomes.
- **Dike Model and Other Supporting Functions**: Core model and utility scripts for hydrology, economics, and network generation.

## Getting Started

1. **Install dependencies**  

   Use the provided `requirements.txt`:
   
   ```sh
   pip install -r requirements.txt
2. **Run Notebooks**

    Open the notebooks (00-04) in the final assignment/ folder with Jupyter or VS Code and follow the instructions in each notebook.

## Results

The full analysis, discussion, and policy recommendations will be included in the final report submitted on Brightspace.