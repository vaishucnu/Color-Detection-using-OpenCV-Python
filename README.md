# 🎨 Color Detection Using Python and OpenCV

This project enables automatic color detection from images or live video streams using Python and OpenCV. By clicking on any pixel within an image or webcam feed, the system identifies the color name based on predefined RGB values. It's a practical tool for graphic designers, developers, or anyone needing precise color identification from digital media.

---

## 🚀 How It Works

1. **Interactive Color Detection**  
   - Users can click anywhere on an image or video frame.
   - The app retrieves the RGB values of the clicked pixel.
   - It compares those values with a predefined color dataset to find the closest named color.

2. **Real-Time Webcam Support**  
   - In live video mode, color detection updates dynamically as you hover your mouse.
   - The current color name and RGB values are displayed on the frame in real-time.

3. **Color Database Matching**  
   - The program uses a CSV or dictionary-based color database with common color names.
   - It calculates the minimum distance between the clicked RGB and known colors to determine the closest match.

---

## 🔑 Key Features

- ✅ **Real-Time Color Detection**  
  Detect and label colors instantly by clicking on them in an image or moving your cursor over a live video feed.

- 🎥 **Webcam & Image Input Support**  
  Works with both static images (PNG, JPG, BMP, etc.) and real-time video from a connected webcam.

- 🧮 **Accurate Color Matching**  
  Uses RGB distance calculation to find and display the most accurate named color.

- 📦 **Built with OpenCV**  
  Leverages OpenCV for fast, efficient image and video processing.

- 🖱️ **Simple & Intuitive UI**  
  Just run the script and click on the area of interest to detect the color—no complicated setup required.

---
## 🚀 Getting Started

### Run the Program:
Execute the script:

```bash
python color_detector.py
```
### Interact with the Program:

- **For static images**:  
  Click on any part of the image to detect its color.

- **For webcam live video**:  
  Move your mouse over the video feed to identify colors dynamically.

---

## 🖥️ Output

Once the user clicks on a pixel or hovers over a color in the live video feed, the program will display:

- **Color Name**: The name of the detected color.
- **RGB Values**: The exact RGB values of the selected pixel.

### Example:

| **Color** | **RGB**       |
|-----------|---------------|
| **Red**   | (255, 0, 0)   |
| **Green** | (0, 255, 0)   |
| **Blue**  | (0, 0, 255)   |

---

## 📁 Supported Formats
- Images: .png, .jpg, .jpeg, .bmp
- Video: Live webcam feed (via OpenCV)

---

## 🔮 Future Enhancements:

- **Extended Color Database**  
  Add more color names and ranges for greater accuracy in color detection. Support for additional color spaces like **HSB** or **LAB** could improve matching precision.

- **User Interface (UI) Enhancements**  
  Provide a graphical interface to upload images or video files directly for color analysis, offering a more user-friendly experience.

- **Custom Color Range**  
  Allow users to define their own color ranges or upload custom color datasets for tailored color detection.
