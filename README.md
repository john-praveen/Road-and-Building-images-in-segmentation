# Road and Building Segmentation in Satellite Images

**Author:** Praveen V.V.J  

This project implements a custom Convolutional Neural Network (CNN) to segment roads and buildings in satellite images. The model is trained on the OpenEarthMap Kaggle dataset and performs pixel-level land cover segmentation on diverse geographic regions. Preprocessing of satellite images ensures accurate feature extraction for urban and rural mapping.



---

## About the Dataset

**Dataset Name:** Global Land Cover Mapping - OpenEarthMap  
**Link:** [Kaggle - OpenEarthMap](https://www.kaggle.com/datasets/aletbm/global-land-cover-mapping-openearthmap/data?select=images)

**Source of Imagery:**  
The dataset combines images from multiple benchmark datasets (xBD, Inria, Open Cities AI, SpaceNet, Landcover.ai, AIRS, GeoNRW, HTCD) along with publicly available aerial images from regions not covered in existing datasets, such as Peru and Japan. Data were collected from OpenAerialMap and geospatial agencies.

**Content:**  
- Multi-region coverage ensures the model generalizes across different geographies.
- Preprocessing is required to normalize and align images for CNN input.

---

## Features

- Custom CNN architecture for road and building segmentation.
- Processes preprocessed multi-region satellite images.
- Generates pixel-level segmentation masks.
- Includes preprocessing, training, evaluation, and visualization scripts.
- Useful for urban planning, disaster management, and land cover analysis.

---





