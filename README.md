# Depth Anything V2

A powerful deep learning project that converts 2D images into 3D depth maps using state-of-the-art vision transformers. This project leverages the DinoV2 model for accurate depth estimation from single images.

## Features

- 2D to 3D depth estimation using DinoV2 model
- Support for both indoor and outdoor images
- Interactive 3D visualization using Open3D
- Easy-to-use Jupyter notebook interface
- Sample images included for testing

## Prerequisites

- Python 3.x
- PyTorch
- Transformers
- Open3D
- OpenCV
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Depth_Anything_V2.git
cd Depth_Anything_V2
```

2. Install the required dependencies:
```bash
pip install torch transformers open3d opencv-python numpy matplotlib
```

## Project Structure

```
Depth_Anything_V2/
├── 2D_To_3D_DinoV2.ipynb    # Main Jupyter notebook
├── sample_images/           # Sample images for testing
│   ├── indoor/             # Indoor scene images
│   └── outdoor/            # Outdoor scene images
└── outputs/                # Generated depth maps and 3D models
```

## Usage

1. Open the `2D_To_3D_DinoV2.ipynb` notebook in Jupyter
2. Run the cells sequentially to:
   - Load and process images
   - Generate depth maps
   - Create 3D point clouds
   - Visualize results

## Sample Images

The project includes sample images from the Indoor-Outdoor dataset. You can find more images at:
[Indoor-Outdoor dataset](https://figshare.com/articles/dataset/Indoor-Outdoor_dataset/4595323)

## Results

The project generates:
- Depth maps from input images
- 3D point cloud representations
- Interactive 3D visualizations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- DinoV2 model from Hugging Face Transformers
- Open3D for 3D visualization
- Indoor-Outdoor dataset contributors 