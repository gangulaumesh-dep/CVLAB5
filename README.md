# Gray Level Slicing in Image Processing

This script demonstrates Gray Level Slicing techniques in Computer Vision. It enhances specific ranges of gray levels in an image, isolating features of interest, and visualizes the results with and without retaining the original background.

## Prerequisites

Ensure you have the required Python libraries installed:

    pip install opencv-python matplotlib numpy

## How to Use

1. Update the image path in the script. It currently reads from `/content/drive/MyDrive/womancat.webp`. Change this to your local image path:
       
       img = cv2.imread('path/to/your/image.webp', 0)
       
2. Adjust the desired intensity range `r_min` and `r_max` if needed.
3. Run the script in your terminal or Python environment.
### Note: You can directly open the `.ipynb` file in Colab or Jupyter Notebook.

## How it Works

OUTPUT:-

<img width="914" height="836" alt="image" src="https://github.com/user-attachments/assets/11101e92-0249-47c4-924a-5a2fa11f8b19" />
