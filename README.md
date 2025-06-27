# MultiPlanar Reconstruction (MPR) Tool

This project is a **Medical Image Multi-Viewer** tool designed to visualize medical images in **axial**, **coronal**, and **sagittal** planes. The application provides a user-friendly interface with features to manipulate image views, adjust brightness and contrast, and zoom into specific regions of interest. The tool supports medical image files in the **NIfTI format (.nii, .nii.gz)**.

---
 ![Loading Animation](https://raw.githubusercontent.com/3bdullah-Gamil/mpr-medical-imaging/main/results/reconstructed_video.gif)

 ## 📋 Project Overview
This MultiPlanar Reconstruction (MPR) tool was developed as part of the Introduction to Imaging and Image-Based Anatomy course at the Faculty of Engineering, Cairo University. The project provides detailed views of anatomical structures for diagnostic purposes through interactive multiplanar visualization.

## 🎯 Features

### Core Functionality

- **Interactive Multiplanar Views**: Navigate through axial, sagittal, and coronal planes
- **Dynamic Image Adjustments**: Real-time zoom, brightness, and contrast controls
- **Precise Slice Alignment**: Accurate reconstruction with real-time slice positioning
- **Region Selection**: User-friendly interface for easy navigation and anatomical region selection

### Technical Capabilities

- **Efficient Memory Management**: Optimized handling of large medical datasets (NIfTI File Support) using NumPy arrays
- **Responsive GUI**: Multi-threading implementation for smooth user experience
- **Real-time Processing**: Instant updates across all viewing planes


## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **PyQt5**: GUI framework for desktop application
- **SimpleITK**: Medical image processing and I/O operations
- **Matplotlib**: Visualization and plotting capabilities
- **NumPy**: Efficient array operations and memory management
- **Threading**: Multi-threading for responsive user interface

## 📦 Installation

### Prerequisites
```bash
   pip install python>=3.7
   ```
### Dependencies
```bash
pip install PyQt5
pip install SimpleITK
pip install matplotlib
pip install numpy
   ```
### Clone Repository
```bash
   git clone https://github.com/3bdullah-Gamil/mpr-medical-imaging.git
cd mpr-medical-imaging
   ```
   
## 🚀 Usage
### Running the Application
```bash
   python main.py
   ```

### Loading Medical Data

1.Launch the application
2.Click "Load Dataset" or use File menu
3.Select your CT/MRI dataset (DICOM format supported)
4.The tool will automatically generate multiplanar views

### Navigation Controls

- **Slice Navigation**: Use scroll wheel or slider controls
- **Zoom**: Mouse wheel or zoom controls
- **Brightness/Contrast**: Adjust using dedicated sliders
- **Pan**: Click and drag to move around the image



## 📁 Project Structure
```bash
   mpr-medical-imaging/
├── README.md                    # Main project documentation
├── requirements.txt             # Python dependencies
├── setup.py                     # Package installation script
├── .gitignore                   # Git ignore file
├── src/                        # Source code directory
│   ├── mpr_code.py
├── dataset                       # Sample data and test files
├── results

   ```

## Example Views
### **Axial View**
<img src="https://raw.githubusercontent.com/3bdullah-Gamil/mpr-medical-imaging/main/results/axial_view.png" alt="Axial View" width="400" height="300" />

### **Coronal View**
<img src="https://raw.githubusercontent.com/3bdullah-Gamil/mpr-medical-imaging/main/results/coronal_view.png" alt="Coronal View" width="400" height="300" />

### **Sagittal View**
<img src="https://raw.githubusercontent.com/3bdullah-Gamil/mpr-medical-imaging/main/results/sagittal_view.png" alt="Sagittal View" width="400" height="300" />

---

## 🎓 Academic Context
- **Course**: Introduction to Imaging and Image-Based Anatomy
- **Institution**: Faculty of Engineering, Cairo University
- **Department**: Systems and Biomedical Engineering
- **Supervised By**: Prof. Tamer Basha & Prof. Aliaa Rehan


## Known Limitations

- Currently supports only `.nii` and `.nii.gz` file formats.
  
## 🚧 Future Enhancements
### Planned Features

- 3D Rendering Integration: Full volumetric visualization capabilities
- AI-Powered Segmentation: Automatic organ and structure identification
- GPU Acceleration: CUDA support for faster processing
- Advanced Measurement Tools: Distance, angle, and volume calculations
- DICOM Export: Save processed images in standard medical format

### Technical Improvements

- Real-time 3D Reconstruction: Live volume rendering
- Advanced Filtering: Noise reduction and enhancement algorithms

## 👥 Team Members

- **Abdullah Gamil** 
- **Mohamed Badawy** 
- **Rowaida Mohamed** 
- **Yomna Sabry** 

## 🙏 Acknowledgments

- Faculty of Engineering, Cairo University
- Course instructors and teaching assistants
- Open-source medical imaging community
- SimpleITK and PyQt5 development teams
##

 Note: This tool is developed for educational and research purposes. For clinical use, please ensure compliance with relevant medical imaging standards and regulations.
