# README

## Data Processing and Feature Extraction

This repository contains a comprehensive suite of scripts designed for robust data processing and feature extraction across multiple domains. From analyzing packet captures to augmenting image datasets, each component offers powerful functionality tailored to specific data types. Below are the main features and usage instructions for each component:

### 1. Packet Analyzer

- **Description:** The Packet Analyzer script delves into packet captures (pcap) to extract vital information such as source and destination IPs, ports, protocol details, sequence numbers, and flags.
  
- **Usage:** Simply execute the Packet Analyzer script to initiate the analysis of pcap files. The script automatically generates corresponding CSV files containing detailed packet data for further examination.

### 2. Binary Batching

- **Description:** This module processes CSV files containing packet data and efficiently batches them into pickle files, optimizing data organization and accessibility for subsequent analysis.
  
- **Usage:** Execute the Binary Batching script to seamlessly process CSV files into easily manageable and analyzable pickle file batches.

### 3. Image Converter

- **Description:** The Image Converter script is designed to transform binary data from pickle files into visually interpretable images, leveraging a variety of color maps and pixel layouts to provide valuable insights into the underlying data patterns.
  
- **Usage:** Run the Image Converter script to convert binary data into images using the `scurve` or `hilbert` options to specify the space-filling curve. Please note that the preprocessing step may take up to 30 hours due to the complexity of the conversion process.

### 4. Data Augmentation

- **Description:** With the Data Augmentation script, users can augment existing image datasets to enhance their diversity and size. This process involves applying a range of transformations such as flipping, rotation, blurring, and noise addition to create a more robust dataset for training machine learning models.
  
- **Usage:** Utilize the Data Augmentation script to augment your image dataset, thereby enriching its variability and improving model performance.

## Main Features with Explanations

- **Versatile Data Processing:** Each script offers specialized functionality for processing data from different sources, ensuring versatility and adaptability across various domains. This enables users to handle diverse datasets efficiently.

- **Automated Analysis:** The scripts automate the tedious task of data analysis, providing streamlined workflows for extracting valuable insights from raw data. This saves time and effort by automating repetitive tasks.

- **Efficient Batch Processing:** The Binary Batching script optimizes data organization by efficiently batching CSV files into pickle files, enhancing accessibility and ease of analysis. This improves data management and simplifies subsequent processing steps.

- **Visual Data Representation:** The Image Converter script facilitates visual interpretation of binary data by converting it into images, enabling intuitive analysis and pattern recognition. This aids in understanding complex data structures and identifying meaningful patterns.

- **Enhanced Dataset Generation:** With the Data Augmentation script, users can effortlessly augment image datasets, empowering them to create larger and more diverse datasets for training machine learning models. This improves the robustness and generalization capabilities of machine learning models.
