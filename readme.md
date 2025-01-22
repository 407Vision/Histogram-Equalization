# Enhancing Low-Contrast Images Using Histogram Equalization and CLAHE

---

## Title Slide
**Title**: Enhancing Low-Contrast Images Using Histogram Equalization and CLAHE  
**Presented by**: Group Six (6)  
**Course**: DCIT 407  
**Date**: 22nd January, 2025  

---

## Problem Statement

### What is the Problem?
Low-contrast images make it difficult to see details because pixel intensities are clustered in a narrow range.  

**Examples**:
- Poorly lit photos
- Images with similar brightness across the scene  

### Solution:
Use image processing techniques to enhance contrast.

---

## Objectives of the Assignment
### What Will We Achieve?
1. Implement two image enhancement techniques:
   - **Histogram Equalization**
   - **CLAHE (Contrast Limited Adaptive Histogram Equalization)**  
2. Compare their effects on a low-contrast image.  
3. Understand the strengths and limitations of each method.

---

## Key Concepts

### Histogram Equalization
**What is Histogram Equalization?**  
A global technique to improve image contrast by redistributing pixel intensity values.  

**How it works**:
1. Analyzes the intensity histogram of the image.  
2. Spreads pixel intensities across the available range.  

**Benefits**:
- Enhances global contrast.  

**Limitations**:
- May over-enhance or wash out details in some regions.

---

### CLAHE (Contrast Limited Adaptive Histogram Equalization)
**What is CLAHE?**  
A localized technique for enhancing image contrast.  

**How it works**:
1. Divides the image into smaller grids (tiles).  
2. Applies histogram equalization to each grid.  
3. Limits contrast amplification to avoid over-enhancement.  

**Benefits**:
- Improves localized contrast.  
- Prevents over-brightening.  

**Applications**:
- Medical imaging
- Low-light photography
- Satellite imagery

---


### Contributors:

| **Name**           | **ID**              |
|---------------------|-----------------------|
| Joseph Tackie          | 10982383            |
| Adjei Daniel Junior         | 10970871     |
| Essilfie Prince Bondzie      | 10957300|
| Frank Owusu Appiah       | 10990607|
| Luke Boateng Agyenim       | 10964715|
| Osborn Mensah       | 10966038   |