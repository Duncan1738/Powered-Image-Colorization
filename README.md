#  AI-Powered Image Colorization

A **Deep Learning-based image colorization tool** that converts **black-and-white photos into color** automatically! Powered by **OpenCV & Deep Learning**.

##  Features
-  Uses a **pretrained Deep Learning model**.
-  Converts **grayscale images** into **color**.
-  Lightweight & Fast.

## Installation
```sh
pip install numpy opencv-python argparse


Download the pretrained models:
wget https://raw.githubusercontent.com/richzhang/colorization/master/colorization_deploy_v2.prototxt
wget https://raw.githubusercontent.com/richzhang/colorization/master/colorization_release_v2.caffemodel
wget https://raw.githubusercontent.com/richzhang/colorization/master/pts_in_hull.npy

 How to Use

python colorize.py path/to/your/image.jpg

The colorized image will be saved as colorized.png.

 Example Usage
Input: Black & White Image

Output: Colorized Image

 Future Enhancements
 Train on Custom Datasets
 Add a Web Interface
📷 Batch Image Processing
👥 Contributors
Duncan Kibet - GitHub Profile
📜 License
This project is under the MIT License. Modify and enjoy! 🚀🎨

---

## **🎨 How It Works**
1. **Loads a grayscale image** 📷.
2. **Uses OpenCV's pre-trained model** to generate **color information** 🎨.
3. **Outputs a colorized version** of the image.

---

## **🔥 Why This Project is Cool**
- **AI + Computer Vision**
- **Useful for restoring old black-and-white photos**
- **Lightweight & works instantly**

Would you like me to **add a web interface (Flask) for real-time colorization**? 🚀🔥

