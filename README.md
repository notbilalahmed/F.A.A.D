# F.A.A.D (Flood Affected Areas Detection) Model

This repository contains the **F.A.A.D (Flood Affected Areas Detection)** model, which uses deep learning to detect and classify regions affected by floods in satellite imagery. This model can aid in disaster response by identifying impacted areas, helping with relief efforts, and improving situational awareness during floods.

### Features
- **Satellite Image Processing**: Utilizes satellite data to detect and classify flood-affected regions.
- **Deep Learning Model**: Trained on image data to distinguish between flood and non-flood areas.
- **Real-Time Prediction**: Capable of processing new satellite images and providing fast predictions on flood severity.

### Requirements
To run this project locally, you need the following dependencies:

- Python 3.8+
- Jupyter Notebook
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/faad.git
   cd faad
   ```

2. **Set up a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required libraries**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter Notebook**
   ```bash
   jupyter notebook faad.ipynb
   ```

### Usage

1. **Prepare your dataset**: Place your satellite images in the appropriate folders as specified in the notebook.
2. **Train the Model**: Open the `faad.ipynb` file and follow the instructions to train the model on your dataset.
3. **Test the Model**: Upload new satellite images to test the detection model.

### Example Output

The model will output an annotated satellite image, with flood-affected areas clearly marked for easy identification.
