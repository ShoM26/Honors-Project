# Honors-Project
# Multilingual Handwriting Recognition for Historical Vital Records

**An Honors Research Project extending deep learning approaches for offline handwriting recognition in Birth, Marriage, and Death documents across multiple languages and time periods.**

## Abstract

This project develops a multilingual object detection and OCR pipeline for extracting handwritten information from historical vital records (Birth, Marriage, and Death certificates) using YOLOv8 and deep learning OCR. Building upon Dr. Nishat Majid's foundational work in document processing, this research extends the capability to handle documents from multiple languages, countries, and time periods with a unified model architecture.

## Key Features

- **Multilingual Support**: Unified model capable of processing documents in multiple languages
- **Semantic Region Detection**: YOLOv8-based detection of meaningful text regions (names, dates, places)
- **Historical Document Robustness**: Handles varying document quality, formats, and handwriting styles
- **End-to-End Pipeline**: Complete workflow from raw document images to structured text extraction
- **Web-Scale Validation**: Additional validation dataset scraped from diverse web sources

## Architecture

```
Input Document → YOLOv8 Detection → Semantic Region Extraction → CNN-based OCR → Structured Output
```

**Detection Model**: Ultralytics YOLOv8 for semantic text region identification  
**Recognition Model**: Off-the-shelf OCR model
**Training Strategy**: Transfer learning with multilingual data augmentation

## Dataset

- **Primary Dataset**: BMD (Birth/Marriage/Death certificates)
- **Augmentation**: Roboflow-based data augmentation for increased dataset diversity
- **Validation Data**: Web-scraped documents from multiple countries and time periods
- **Annotation**: Semantic bounding boxes for meaningful text regions (bride's name, date of marriage, place of birth, etc.)

*Note: Dataset availability and access instructions will be updated based on privacy requirements.*

## Repository Structure

```

```

## Results

### Performance Metrics
*[To be added upon completion]*
- Detection Accuracy (mAP@0.5): 
- Recognition Accuracy (Character-level): 
- End-to-End Accuracy: 

### Sample Outputs
*[Demo images showing before/after processing will be included]*

## Technical Contributions

This work extends existing document processing research with the following novel contributions:

1. **Multilingual Unified Architecture**: Single model handling multiple languages vs. language-specific models
2. **Historical Document Robustness**: Enhanced performance on documents with varying age and quality
3. **Completing the OCR part of the pipeline**: The model will predict a text outcome from the given written text fields

## Related Work

This project builds upon the foundational research by Dr. Nishat Majid in Offline Handwritting Recognition. Key differences and extensions:
- Increased Computing Power
- Recent Industry Inovations
- Completing the OCR pipeline

## Citation

If you use this work in your research, please cite:

```bibtex

```

## Acknowledgments

- Dr. Nishat Majid for foundational research and guidance
- Ohio Dominican University Honors Program
- Roboflow for data management platform
- Ultralytics for YOLOv8 framework

## Contact

Merrick Shorter - shorterm@ohiodominican.edu  
Linkedin URL - https://www.linkedin.com/in/merrick-shorter/

---
*This project was completed as part of an Honors Research Program at Ohio Dominican University under the supervision of Dr. Nishat Majid.*

