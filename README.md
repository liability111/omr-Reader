# omr-Reader
A Python-based Optical Mark Recognition (OMR) tool designed to evaluate exam sheets efficiently. This tool leverages OpenCV and Streamlit to detect, preprocess, and evaluate OMR sheets, providing an accurate and user-friendly solution for educational and professional use.

# Features

Automatic Rotation Detection: Corrects skewed or rotated OMR sheets using Hough Line Transform.

Preprocessing and Noise Reduction: Ensures accurate evaluation by applying Gaussian blur and adaptive thresholding.

Contour Detection: Identifies and extracts the sheet area using perspective transformation.

Bubble Detection: Accurately identifies marked answers using contour analysis.

Customizable Answer Key: Users can define the correct answers through a simple sidebar interface.

Score Calculation: Computes the score and overlays it on the processed sheet image

# Usage

Upload OMR Sheet:

Launch the application and upload a scanned OMR sheet in JPG or PNG format.

Define Answer Key:

Use the sidebar to specify the correct answers for the questions.

Evaluate:

The tool detects the marked answers, evaluates them against the answer key, and calculates the score


# File Structure
|-- app.py                 # Main application file
|-- requirements.txt       # Python dependencies
|-- README.md              # Project documentation
|-- assets/                # Folder for example images/screenshots

# Technologies Used

Python: Core programming language.

OpenCV: Image processing and contour detection.

Streamlit: Web interface for user interaction.

NumPy: Efficient array operations.

# Future Scope

Enhance detection accuracy for images rotated beyond 32 degrees.

Integrate deep learning models for fault-tolerant OMR evaluation.

Support for multi-type questions, including subjective answers.

Deploy the application on cloud platforms for broader accessibility.




# For Demo
run the main.py file in any python interpretor
install the dependencies and libraries 
run the file : streamlit run main.py
upload the omr sheet
check the answer key
wait for evaluation

