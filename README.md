# Smart-Color-Recognition-and-Product-Sorting-System:

📌Project Description:
       Smart Color Recognition and Product Sorting System is a smart automation project that identifies products based on their
color and automatically sorts them into different categories. The system uses a  RGB led to detect the color of an object
and controls the sorting mechanism accordingly. this helps reduce manual effort,improve accuracy,and increase efficiency 
in industrial production and packaging processes.

✡️Key Features:
  -Automatic color detection.
  -Real time product sorting.
  -High accuracy and efficiency.
  -Reduce humann intervention.
  -Suitable for industrial automation applications.

  ⛏️Components used:
  -Arduino Uno 
  -RGB led
  -3*Resistors(RGB led current limiting)
  -Servo motor
  -Sound Sensor

  **Methodology:
  -The system detects the color of product using a color sensing mechanism.
  -The detected color data is processed by the controller.
  -Based on the identified color,the product is classified into the corresponding category.
  -The sorting mechanism automatically directs the product to the appropriate section.
  -The process is repeated continuously for real time product sorting.

  **Color Detection Process:
1.Image Acquisition:
      Capture images of the products using a camera. Ensure that the lighting is consistent to avoid shadows and reflections that can affect color perception.
2.Preprocessing:
      ~Resize Images: Scale the images to a manageable size for processing.
      ~Noise Reduction: Apply smoothing techniques like Gaussian blur to reduce noise in the image.
      ~Color Space Conversion: Convert the image from the RGB color space to another color space that may be more suitable for color detection, such as HSV (Hue, Saturation, Value) or LAB.
3.Color Segmentation:
      ~Define a range for each color you want to detect. For example, you can set lower and upper bounds for hues in the HSV color space to isolate specific colors.
      ~Use a thresholding technique to create a binary mask that highlights the pixels falling within the defined color range.
4.Contouring and Object Detection:
      ~Find contours in the binary mask created in the previous step. This will help you identify distinct objects in the image.
      ~Filter detected contours based on size or shape to eliminate noise or irrelevant artifacts.
5.Color Classification:
      ~For each detected object, calculate the average color or dominant color within the contour.
      ~Compare the dominant color to predefined color categories to classify the product.
6.Sorting Logic:
      ~Based on the classification, route or sort the products into different bins or storage areas according to their detected colors. This can be done 
physically (using conveyor belts, robotic arms, etc.) or digitally (in a database).
7.Feedback Loop:
      ~Optionally, implement a feedback mechanism that allows for corrections in case of misclassification. Use this data to retrain your model if you are using machine learning techniques for better accuracy.

**Result:    
 -The system successfully detected different product colors.
 -Products were automatically stored based on their identified color.
 -The sorting process was accurate and efficient.
 -The project demonstrate the concept of industrial automation using color-based classification.

 **Real Time Application:
 -Manufacturing industries.
 -Packaging and Sorting units.
 -Quality control system.
 -Automated Production lines

 **Future Enhancement:
 -Suppport for multiple product categories.
 -IoT-based remote monitoring.
 -Higher sorting speed and accuracy.

**Project files:
-Arduino Uno source code.
-Circuit diagram.
-Working Demonstration video
 

  
  
  


