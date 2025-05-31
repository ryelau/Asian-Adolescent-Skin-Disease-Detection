# Asian Adolescent Skin Disease Detection

An AI-powered application for detecting and analyzing 14 common skin conditions affecting Asian adolescents through facial image analysis.

## Project Overview

This project uses deep learning and computer vision techniques to identify skin conditions from user-submitted facial images. The AI analyzes images to detect symptoms, classify their severity (mild, moderate, severe), and provide appropriate treatment recommendations or medical referrals.

## Key Features

- **Automated Detection**: Upload a facial image to receive instant analysis
- **14 Condition Recognition**: Identifies common skin conditions in Asian adolescent populations
- **Severity Classification**: Categorizes conditions as mild, moderate, or severe
- **Treatment Recommendations**: Provides care plans for mild/moderate conditions
- **Medical Referral**: Suggests professional consultation for severe cases
- **Treatment Planning**: Generates personalized treatment schedules

## Skin Conditions Detected

The AI system is trained to recognize the following 14 conditions:

1. Acne (痤疮/青春痘)
2. Eczema/Atopic Dermatitis (湿疹/特应性皮炎)
3. Seborrheic Dermatitis (脂溢性皮炎)
4. Rosacea (玫瑰痤疮/酒渣)
5. Contact Dermatitis (接触性皮炎)
6. Photodermatitis (日光性皮炎/光敏性皮炎)
7. Herpes Zoster/Shingles (带状疱疹)
8. Herpes Simplex (单纯疱疹)
9. Facial Psoriasis (银屑病面部型)
10. Melasma (黄褐斑)
11. Folliculitis (毛囊炎)
12. Perioral Dermatitis (口周皮炎)
13. Pityriasis Versicolor (白色糠疹)
14. Milia (粟丘疹/脂肪粒)

## How It Works

1. **Image Submission**: Users upload facial images through the application
2. **AI Analysis**: Deep learning models process and analyze the image
3. **Condition Detection**: The system identifies present skin conditions
4. **Severity Assessment**: Each condition is classified by severity level
5. **Recommendation Generation**: The system provides appropriate guidance:
   - **Mild/Moderate Cases**: Treatment recommendations, medication suggestions, usage instructions
   - **Severe Cases**: Medical referral recommendations

## Project Structure

```
├── data/                       # Dataset storage and processing scripts
│   ├── raw/                    # Raw training images
│   ├── processed/              # Preprocessed images
│   └── annotations/            # Condition labels and metadata
├── models/                     # Neural network model definitions
│   ├── detection/              # Condition detection models
│   ├── classification/         # Severity classification models
│   └── saved_models/           # Trained model checkpoints
├── src/                        # Source code
│   ├── preprocessing/          # Image preprocessing utilities
│   ├── training/               # Model training scripts
│   ├── inference/              # Inference pipeline
│   ├── api/                    # API endpoints
│   └── utils/                  # Helper functions
├── frontend/                   # User interface components
├── recommendations/            # Treatment recommendation system
│   ├── medications/            # Medication database
│   └── treatment_plans/        # Treatment plan templates
├── tests/                      # Testing framework
├── docs/                       # Documentation
├── requirements.txt            # Python dependencies
├── setup.py                    # Installation script
└── README.md                   # Project documentation
```

## Installation

```bash
# Clone the repository
git clone https://github.com/username/Asian-Adolescent-Skin-Disease-Detection.git
cd Asian-Adolescent-Skin-Disease-Detection

# Create and activate virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up the application
python setup.py
```

## Usage

```bash
# Start the application
python src/app.py

# The web interface will be available at http://localhost:5000
```

## Technology Stack

- **Machine Learning**: PyTorch/TensorFlow, OpenCV
- **Backend**: Flask/FastAPI
- **Frontend**: React/Vue.js
- **Database**: MongoDB/PostgreSQL
- **Deployment**: Docker, Kubernetes

## Contribution Guidelines

We welcome contributions to improve the detection accuracy and expand the capabilities of this project.

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/your-feature-name`
3. **Commit** your changes: `git commit -m 'Add some feature'`
4. **Push** to your branch: `git push origin feature/your-feature-name`
5. Submit a **Pull Request**

### Contribution Areas

- Dataset expansion with diverse skin types and conditions
- Model optimization for better accuracy
- Adding new skin conditions to the detection scope
- Improving treatment recommendations
- Enhancing the user interface
- Documentation and translations

## Ethical Considerations

- This application is designed as a screening tool and does not replace professional medical diagnosis
- Patient privacy and data security are prioritized in all aspects of the system
- The AI models are continuously evaluated for biases across different ethnicities and skin tones

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Medical professionals who provided expertise and validation
- Contributors to the training dataset
- Open-source AI and machine learning communities

## Contact

For questions or suggestions, please contact [mirrorAI@163.com](mailto:mirrorAI@163.com).
