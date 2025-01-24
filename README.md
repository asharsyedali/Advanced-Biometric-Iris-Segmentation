# Advanced Biometric Identification Using U-Net for Iris Segmentation

## Description
This project implements a deep learning-based iris segmentation system using U-Net architecture. The solution addresses challenges such as varying illumination, occlusion, and noise to provide accurate and efficient iris segmentation for biometric applications.

## Features
- **Advanced U-Net Architecture**: Enhanced with additional convolutional layers and dropout for improved generalization.
- **High Accuracy**: Achieves a Dice Coefficient of 0.92 and IoU of 0.87 on the MMU1 Iris dataset.
- **Robust Performance**: Handles challenging conditions such as noise, occlusions, and uneven lighting.
- **Data Augmentation**: Incorporates random rotations, flips, and brightness adjustments to improve model robustness.

## Dataset
The project utilizes the **MMU1 Iris Dataset**, which consists of 920 iris images captured under diverse imaging conditions. Preprocessing includes resizing images to 128x128 pixels and normalizing pixel values.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/asharsyedali/Advanced-Biometric-Iris-Segmentation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Advanced-Biometric-Iris-Segmentation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the dataset:
   - Download the MMU1 Iris dataset and place it in the `data/` directory.
   - Ensure images are preprocessed (resized to 128x128 pixels).

2. Train the model:
   ```bash
   python train.py
   ```

3. Evaluate the model:
   ```bash
   python evaluate.py
   ```

4. Visualize the results:
   - View segmented outputs compared to ground truth masks in the `results/` directory.

## Results
### Quantitative Metrics
- **Dice Coefficient**: 0.92
- **Intersection over Union (IoU)**: 0.87

### Visual Results
Representative examples highlight the model's ability to handle:
- Occlusions
- Uneven illumination
- Noise

## Future Work
- **Real-Time Deployment**: Optimize for edge devices like smartphones.
- **Hybrid Systems**: Integrate iris segmentation with face recognition for enhanced security.
- **Dataset Diversity**: Expand training data to include diverse demographics and imaging conditions.
- **AR/VR Applications**: Explore iris recognition for secure, personalized experiences in augmented and virtual reality.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgment
This project was supervised by **Professor Zunnurain Hussain**, University of Management and Technology, Lahore.

## Contact
- **Syed Mohammad Ali Ashar**: [f2022376084@umt.edu.pk](mailto:f2022376084@umt.edu.pk)
