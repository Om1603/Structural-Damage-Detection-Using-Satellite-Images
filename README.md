# Disaster Assessment Tool

This tool is designed to assist in the assessment of disaster-affected areas using image processing techniques. It allows for the extraction, processing, and visualization of pre and post-disaster images, aiding in the identification of damaged regions.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Requirements

To run the Disaster Assessment Tool, you need to have the following installed:

- Python 3.x
- Tkinter
- OpenCV (cv2)
- NumPy
- Matplotlib
- TensorFlow

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your_username/disaster-assessment-tool.git
    ```

2. Navigate to the project directory:

    ```bash
    cd disaster-assessment-tool
    ```

3. Install the required Python packages using pip:

    ```bash
    pip3 install -r requirements.txt
    ```

## Usage

1. Ensure you have met all the requirements and installed the necessary packages as mentioned above.

2. Run the `main.py` file:

    ```bash
    python3 main.py
    ```

3. The Disaster Assessment Tool GUI window will open.

4. Click on the "Select ZIP file" button to choose a ZIP file containing pre and post-disaster images.

5. After selecting the ZIP file, choose an extraction directory.

6. The tool will process the images and display the pre and post images along with the computed metrics.

7. Use the "Next" and "Previous" buttons to navigate through the images.

8. To save the displayed images along with their Otsu's thresholds, click the "Save" button and choose a directory to save the files.

9. Close the GUI window when finished.

## Sample Datasets for testing

1. https://drive.google.com/file/d/1G3ogfIhWLvWjjhIyM4Wg9dbO3PrZ9DM-/view?usp=drive_link

2. https://drive.google.com/file/d/1iDBqdD9hW4thOzRPg9SjdJo3t7-St2Oh/view?usp=drive_link



