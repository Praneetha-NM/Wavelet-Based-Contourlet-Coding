# Wavelet-Based Contourlet Coding

Wavelet-Based Contourlet Coding is an advanced image compression technique utilizing the Contourlet Transform and SPIHT-like coding for efficient encoding of grayscale and color MRI images. This project focuses on achieving high compression efficiency while preserving image quality.

## Features
- **Wavelet-Based Contourlet Transform (WBCT)**: Used for multi-directional decomposition of images.
- **SPIHT-like Coding**: Modified SPIHT algorithm for better compression performance.
- **Grayscale & Color Image Compression**: Supports medical image formats.
- **Reconstruction & Quality Evaluation**: Measures compression efficiency using PSNR and SSIM.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: NumPy, OpenCV, PyWavelets, Matplotlib
- **Compression Algorithm**: SPIHT-like coding

## Installation
### Prerequisites
- Python 3.8+
- Required dependencies installed

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Praneetha-NM/Wavelet-Based-Contourlet-Coding.git
   cd Wavelet-Based-Contourlet-Coding
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the compression script:
   ```sh
   python compress.py --input <image_path>
   ```
4. Run the reconstruction script:
   ```sh
   python decompress.py --input <compressed_file>
   ```

## Usage
- Provide an image for compression.
- The system applies WBCT and SPIHT-like coding.
- Decompress the image and evaluate quality metrics.

## Troubleshooting
- Ensure correct image format and dependencies.
- If PSNR is negative, verify image resizing steps.


## Contact
For any queries, feel free to reach out:
- GitHub: [Praneetha-NM](https://github.com/Praneetha-NM)
- Email: [praneetha7597@gmail.com](mailto:praneetha7597@gmail.com)

