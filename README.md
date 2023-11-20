### README.md for "Neural Artistic Style Transfer"

---

#### Overview
"Neural Style Transfer" is a Jupyter notebook that demonstrates the application of Neural Style Transfer (NST), a fascinating technique in the field of deep learning. NST blends the content of one image with the style of another using Convolutional Neural Networks (CNNs). This process creates a unique, synthesized image that retains the content of the target image but mimics the artistic style of the source image.


#### Setup
1. **Install Python**: Make sure Python 3.6 or higher is installed on your system. If not, download and install it from [python.org](https://www.python.org/downloads/).

2. **Set Up a Virtual Environment** (Optional but recommended):
   - Create a new virtual environment:
     ```bash
     python -m venv style-transfer-env
     ```
   - Activate the environment:
     - On Windows: `style-transfer-env\Scripts\activate`
     - On macOS and Linux: `source style-transfer-env/bin/activate`

3. **Install Dependencies**:
   - Ensure pip is up-to-date: `pip install --upgrade pip`
   - Install the required packages:
   ### Required Libraries
   You can install the required libraries using `pip` and the provided `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

   #### List of Dependencies
   - `os`
   - `cv2` (OpenCV)
   - `shutil`
   - `random`
   - `tensorflow`
   - `keras`
   - `PIL` (Pillow)
   - `numpy`
   - `pandas`
   - `matplotlib`
   - `scikit-learn` (for `shuffle`)
   - `functools`
   - `IPython.display`


4. **Download the Notebook**:
   - Download the "Neural Style Transfer" notebook from the provided source.

5. **Launch Jupyter Notebook**:
   - Run `jupyter notebook` in your terminal or command prompt.
   - Navigate to the notebook file and open it.

#### Running the Notebook
- Execute each cell in the notebook in order. The notebook is well-commented, making it easy to understand each step of the NST process.

#### Theoretical Background
- **Neural Style Transfer**: NST uses a pre-trained CNN (like VGG19) to extract content and style features from images. It then optimizes a generated image to match the content of one image and the style of another.
- **Content and Style Representation**: The content of an image is represented by the feature maps of certain layers in the network, whereas the style is represented by the Gram matrices of layers' feature maps.
- **Loss Functions**: NST involves minimizing a combined loss function that comprises content loss (ensuring content similarity) and style loss (ensuring stylistic similarity).

#### Customization
- You can experiment with different content and style images, change the number of iterations, or adjust the style-to-content ratio to see how these changes affect the output.

#### Note
- The process of NST can be computationally intensive. For faster performance, it is recommended to run the notebook on a machine with a capable GPU.

---
Anindya Sen [224102306], IIT Guwahati