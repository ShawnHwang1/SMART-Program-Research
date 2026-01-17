# Identification of Unhealthy Teeth Using Convolutional Neural Networks on the Tufts Dental Datase

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Neural%20Networks-orange.svg)
![Status](https://img.shields.io/badge/status-research-yellow.svg)

## 📋 Overview
This research project earned the Florence Nightingale Award for Statistical Insight at the 2025 Florence Nightingale Symposium at UC Riverside.
This repository contains research work on dental image analysis using deep learning techniques. The project aims to develop automated systems for detecting, classifying, and analyzing dental conditions from clinical images, contributing to smart healthcare and dental informatics.

## 🎯 Project Objectives

- **Automated Dental Detection**: Implement deep learning models to automatically detect and identify teeth in dental images
- **Disease Classification**: Develop neural networks capable of classifying various dental conditions
- **Clinical Application**: Create practical tools that can assist dental professionals in diagnosis and treatment planning
- **Smart Healthcare**: Contribute to IoT-based dental health monitoring systems

## 📁 Repository Structure

```
SMART-Program-Research/
├── Dental.ipynb              # Main dental analysis notebook
├── SMART - EDA.ipynb         # Exploratory Data Analysis
├── Smart - NN.ipynb          # Neural Network implementation
├── teeth_bbox.json           # Bounding box annotations for teeth
├── 96.JPG                    # Sample dental images
├── 997.JPG
├── 998.JPG
├── 999.JPG
└── README.md
```

## 🔬 Technical Approach

### Exploratory Data Analysis (EDA)
The `SMART - EDA.ipynb` notebook contains:
- Data preprocessing and cleaning
- Visualization of dental image datasets
- Statistical analysis of image features
- Pattern identification in dental conditions

### Neural Network Architecture
The `Smart - NN.ipynb` notebook implements:
- Deep learning models for dental image analysis
- Training and validation procedures
- Model evaluation metrics
- Performance optimization techniques

### Dental Detection System
The `Dental.ipynb` notebook focuses on:
- Teeth detection and localization
- Bounding box predictions using annotated data
- Integration with clinical image datasets
- Output visualization and validation

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Jupyter Notebook**: Interactive development environment
- **Deep Learning Frameworks**: Implementation of neural networks
- **Computer Vision**: Image processing and analysis
- **JSON**: Structured data storage for annotations

## 🚀 Getting Started

### Prerequisites

```bash
# Install required dependencies
pip install jupyter
pip install numpy pandas
pip install matplotlib seaborn
pip install scikit-learn
pip install tensorflow  # or pytorch, depending on implementation
pip install opencv-python
pip install pillow
```

### Running the Notebooks

1. Clone the repository:
```bash
git clone https://github.com/ShawnHwang1/SMART-Program-Research.git
cd SMART-Program-Research
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run the notebooks in the following order:
   - Start with `SMART - EDA.ipynb` for data exploration
   - Proceed to `Smart - NN.ipynb` for model training
   - Use `Dental.ipynb` for comprehensive dental analysis

## 📊 Dataset Information

The project utilizes:
- Clinical dental images (JPG format)
- Annotated bounding boxes for teeth detection (`teeth_bbox.json`)
- Various dental conditions and pathologies
- High-resolution periapical or clinical dental photographs

## 🔍 Key Features

### 1. Teeth Detection
- Automatic identification of individual teeth in dental images
- Bounding box generation and localization
- Support for various image formats and resolutions

### 2. Disease Classification
- Multi-class classification of dental conditions
- Support for common dental diseases (caries, plaque, periodontal issues)
- Confidence scoring for predictions

### 3. Data Analysis
- Comprehensive exploratory data analysis
- Visualization of detection results
- Performance metrics and evaluation

## 📈 Research Applications

This work contributes to several areas of dental informatics:

- **Clinical Decision Support**: Assisting dentists in early disease detection
- **Teledentistry**: Enabling remote dental consultations
- **Preventive Care**: Early identification of dental issues
- **Educational Tools**: Training resources for dental students
- **Smart Healthcare Systems**: Integration with IoT dental devices

## 🎓 Research Context

This project aligns with current research in:
- Smart dental health IoT platforms
- Deep learning in medical imaging
- Computer-aided diagnosis in dentistry
- Automated dental radiograph analysis
- Transfer learning for dental applications

## 📝 Future Work

Potential areas for expansion:
- [ ] Expand dataset with more diverse dental images
- [ ] Implement advanced architectures (Faster R-CNN, MASK R-CNN)
- [ ] Add multi-disease classification capabilities
- [ ] Develop web-based deployment for clinical use
- [ ] Integration with dental imaging devices
- [ ] Real-time detection and analysis
- [ ] Mobile application development

## 🤝 Contributing

Contributions are welcome! Areas where help is appreciated:
- Dataset expansion and annotation
- Model optimization and improvement
- Documentation and examples
- Testing and validation
- Clinical feedback and validation

## 📄 License

This project is part of academic research. Please check with the repository owner for specific licensing terms.

## 👥 Authors

- **Shawn Hwang** - [ShawnHwang1](https://github.com/ShawnHwang1)

## 🙏 Acknowledgments

- SMART Program for research support
- Clinical partners for providing dental image datasets
- Open-source community for deep learning frameworks
- Research community in dental AI and medical imaging

## 📧 Contact

For questions, collaborations, or more information about this research:
- GitHub: [@ShawnHwang1](https://github.com/ShawnHwang1)
- Repository: [SMART-Program-Research](https://github.com/ShawnHwang1/SMART-Program-Research)

## 📚 References

This work builds upon research in:
- Dental disease detection using deep learning
- Smart healthcare IoT platforms
- Computer vision in medical imaging
- Automated teeth detection and numbering
- Transfer learning in dental diagnostics

---

*Last Updated: January 2026*
