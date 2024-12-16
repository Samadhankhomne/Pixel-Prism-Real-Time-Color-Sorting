# Pixel-Prism-Real-Time-Color-Sorting

### Overview:
- This project demonstrates real-time color detection and segmentation using Python and OpenCV.
- It identifies specific colors (red, green, blue) in a video stream captured via webcam and isolates them using color masks.

### Key Features:
- Captures real-time video feed from the webcam.
- Converts the captured frames to the HSV color space for easier color processing.
- Detects and highlights red, green, and blue colors using predefined HSV ranges.
- Masks out all other colors to display only the selected colors.
- Provides a composite result showing all colors except white in the feed.

## Technologies Used:
- **Python**: For writing the script.
- **OpenCV**: For image and video processing.
- **NumPy**: For efficient array operations and mask creation.

## How It Works:
1. Reads frames from the webcam feed in real-time.
2. Converts each frame from BGR to HSV color space.
3. Applies specific HSV thresholds for red, green, and blue to create masks for each color.
4. Uses bitwise operations to isolate and display these colors.
5. Includes a general mask to filter all colors except white for a custom result display.

## Applications:
- Real-time object detection based on specific colors.
- Highlighting objects of interest in a video feed.
- Useful for robotics, AR/VR applications, and vision-based tracking.

## Output:
- Displays four live video windows:
  - **Original Frame**: The unprocessed webcam feed.
  - **Red, Green, and Blue Outputs**: Separate windows showing isolated colors.
  - **Composite Result**: Highlights all colors except white.

## Customization:
- Easily adjustable HSV thresholds to detect different colors.
- Expandable to include other colors or perform advanced segmentation tasks.

## Future Enhancements:
- Add support for dynamic threshold adjustments through GUI sliders.
- Integrate tracking capabilities for detected colors.
- Include saving and processing of the video feed with the detected masks.
