# Machine Learning Land Use Classification from Satelite images

## 1. Business / Research Question

### Problem

Can satellite image patches be automatically classified into land use categories to support environmental monitoring and urban planning?

### Motivation

Manual annotation of satellite imagery is costly and time-consuming. Automated classification can:

- Accelerate large-scale analysis
- Support planning and monitoring
- Flag uncertain cases for human review

The system is intended as decision support rather than full automation.

## 2. Dataset

### 2.1 Source

We use the EuroSAT RGB dataset:

- ~27,000 satellite image patches
- 10 land use classes
- RGB format, 64×64 resolution
- Images organized in class-based folders

### 2.2 Classes

- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- Industrial
- Pasture
- PermanentCrop
- Residential
- River
- SeaLake

Each image represents a satellite patch labeled with its dominant land use type.

### 2.3 Dataset Indexing

To prepare the dataset for model training, we construct a master DataFrame containing:

- The image file path
- The corresponding class label

This structured representation will allow us to perform a reproducible train/validation/test split while ensuring consistency across models.



## 4. Model 1: Baseline

## 5. Model 2: CNN


## 6. Comparison of Results


## 7. Limitations and Future Improvements