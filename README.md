# Road-lane-detection
***
### Objective of the project
The objective of this project is to develop a lane detection system that processes video footage to identify and highlight lane markings on roadways. The system provides real-time visual feedback to drivers by overlaying lane boundaries and issuing warnings when the vehicle deviates from its lane. This solution aims to enhance road safety and assist drivers in maintaining proper lane discipline, leveraging image processing techniques such as color space conversion, edge detection, and Hough transforms.
***
### Technical Specifications
- **Programming Language:** Python 3.12.0
- **Libraries Used:**
  - **OpenCV:** 4.10.0
  - **Numpy:** 2.1.1
- **Development Environment:**
  - **Editor:** Visual Studio Code
  - **Notebook Interface:** Jupyter Notebook

The project was developed using Python 3.12.0 with OpenCV 4.10.0 for image processing and lane detection tasks. The code was executed in a Jupyter Notebook environment within Visual Studio Code to facilitate iterative development and testing.
***
### Steps Involved

1. **Data Collection**
   - Gather video footage for lane detection, including different driving scenarios and road conditions.

2. **Preprocessing**
   - **Color Space Conversion:** Convert the image to HSL color space to isolate lane markings.
   - **Grayscale Conversion:** Convert the color image to grayscale to simplify further processing.

3. **Image Smoothing**
   - **Gaussian Smoothing:** Apply Gaussian blur to reduce noise and improve edge detection accuracy.

4. **Edge Detection**
   - **Canny Edge Detection:** Detect edges in the smoothed grayscale image to highlight lane markings.

5. **Region of Interest Selection**
   - **Region Masking:** Define and mask a region of interest in the image to focus on areas where lane markings are likely to appear.

6. **Lane Detection**
   - **Hough Transform:** Apply Hough Line Transform to detect lane lines within the masked region.

7. **Lane Line Drawing**
   - **Drawing Lane Lines:** Overlay detected lane lines on the original image to visualize the lane boundaries.

8. **Feedback Integration**
   - **Visual Feedback:** Draw lane boundary lines and provide warnings if the vehicle deviates from its lane.
   - **Warning Display:** Add text or symbols to indicate lane departure and guide the driver.

9. **Video Processing**
   - **Video Reading and Writing:** Process each video frame by frame, applying the lane detection and feedback functions.
   - **Real-Time Display:** Show the processed video with lane detection and feedback in a window for real-time monitoring.

10. **Output Saving**
    - **Save Processed Video:** Save the processed video with lane markings and feedback to an output folder.

11. **Testing and Validation**
    - **Testing:** Validate the system with different video samples to ensure accuracy and reliability.
    - **Adjustments:** Fine-tune parameters and improve detection based on testing results.
***
Results:

https://github.com/user-attachments/assets/fc2a24ce-f4b6-46d8-9c3e-72f26115c2ad

This video shows that the lane in the road is successfully marked and in case the driver goes out of the lane the alert will be displayed.

Conclusion:
In this Project, the lanes were sucessfully detected and the feedback has been incorporated.


