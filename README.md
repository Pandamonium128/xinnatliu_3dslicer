# 3d slicer project
## Overview
CTChest medical imaging workflow, public dataset CTCHest segmented into bone anatomy, reconstructed to 3d model, exported surface mesh, STL

Towards training LLM models

## core competencies
- DICOM/CT image visualization
- STL model export
- technical documentation
- segmentation refinement

## workflow
1. load CT
2. segment
3. thresholding
4. remove unwanted regions
5. smooth segment
6. gen 3d model
7. export STL

## predicted clinical app
- surgical planning
- medical edu
- anatomy vis
- 3d print
- med device

## limitations
publicly available dataset
not clinically validated

## future work
- manual and semi-automatic segmentation
- automate segmentation, python
- export for CAD implant, surgical guide design
- automation for LLM, generative training

## Software
- 3d slicer 5.10.0
