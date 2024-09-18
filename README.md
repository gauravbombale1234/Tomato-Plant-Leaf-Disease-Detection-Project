# Tomato Plant Leaf Disease Detection and Treatment

## Project Overview

The **Tomato Plant Leaf Disease Detection and Treatment** project utilizes Convolutional Neural Networks (CNN) to identify diseases in tomato plants from leaf images. The system not only detects the disease but also provides treatment recommendations based on the identified condition.

## Features

- **Disease Detection**: Identifies various diseases affecting tomato plant leaves.
- **Treatment Suggestions**: Provides recommended treatments for the detected diseases.
- **User-Friendly Interface**: Allows users to easily upload leaf images and receive results.

## Technologies Used

- **Python**: Main programming language.
- **TensorFlow/Keras**: For building and training the CNN model.
- **OpenCV**: For image preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizing results.

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Tomato-Plant-Leaf-Disease-Detection.git
   cd Tomato-Plant-Leaf-Disease-Detection
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Pre-trained Model** (if applicable):
   - Place the pre-trained model in the `models/` directory.

## Usage

1. **Run the Application**:
   ```bash
   python app.py
   ```

2. **Upload an Image**:
   - Use the web interface to upload a leaf image.
   - The system will process the image and display the detected disease and suggested treatment.

## Impact

- **Enhanced Agricultural Productivity**: By detecting diseases early, the project helps farmers take timely action, reducing crop loss and improving yield.
- **Cost Reduction**: Provides cost-effective solutions for disease management by suggesting appropriate treatments, minimizing the need for expensive diagnostic tools.
- **Sustainable Farming**: Supports sustainable agricultural practices by promoting targeted treatment and reducing the use of unnecessary chemicals.
- **Increased Awareness**: Educates farmers about common diseases and treatments, empowering them to better manage their crops.

## Contributing

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -am 'Add new feature'
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature-branch
   ```
5. **Create a Pull Request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any queries or contributions, please contact:

- **Name**: Gaurav Bombale
- **Email**: gauravbombale1234@gmail.com

## Acknowledgements

- TensorFlow/Keras for providing the framework for building and training the CNN model.
- OpenCV for image preprocessing utilities.
