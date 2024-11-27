# NLLB-Translator
A Japanese-to-English translation app built using Meta's NLLB model, enabling accurate translations and fine-tuning capabilities with open-source corpora.


# Translation App (NLLB-Based)

This repository contains a Japanese-to-English translation application powered by Meta's NLLB (No Language Left Behind) model. The project allows efficient translations and fine-tuning with open-source Japanese-to-English corpora for improved performance.

## Features

- **NLLB Integration**: Leverages the pre-trained NLLB model for accurate translations.
- **Fine-Tuning**: Enhances model performance using custom corpora.
- **Evaluation**: Includes tools to measure translation accuracy.
- **Ease of Use**: Simplified workflows for translation tasks.

## Repository Structure

- `Trans App V2.ipynb`: Main Jupyter Notebook implementing the app.
- `data/`: Contains training and evaluation datasets (add your own datasets here).
- `models/`: Stores fine-tuned model weights.
- `outputs/`: Results and evaluation logs.

## Getting Started

### Prerequisites

- Python 3.8+ (Python 3.11 was used in the project)
- Required libraries: Install dependencies with the following command:

## Requirements
```bash
pip install -r requirements.txt
```

Libraries used are:

transformers==4.34.0
torch==2.0.1
datasets==2.14.5
numpy==1.24.4
pandas==1.5.3
scikit-learn==1.3.2
matplotlib==3.8.0
jupyter==1.0.0


### Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your_username/translation-app.git
   cd translation-app
   ```

2. **Run the Jupyter Notebook**:

   Open `Trans App V2.ipynb` in Jupyter Notebook or JupyterLab and execute cells step by step.

3. **Fine-Tune the Model**:

   Add your Japanese-to-English corpora in the `data/` folder, and follow the notebook's fine-tuning section.

4. **Test Translations**:

   Provide Japanese text inputs and observe the translated outputs.

### Sample Translation

Input: `日本語のテキスト`  
Output: `English translation of the Japanese text`

## Contribution

Contributions are welcome! If you have suggestions or encounter issues, please open an issue or submit a pull request.
Try to upload your weights so that people can easily train there model and improve its efficiency.

## License

This project is licensed under the MIT License.

---

### Acknowledgments

- **Meta's NLLB**: The core translation model powering this app.
- Open-source Japanese-to-English corpora for training data.

---

Happy translating! 🌏


##Hardware Specs for my System

CPU  - i7-13620H
RAM  - 16GB
GPU  - RTX 4070 Laptop GPU
VRAM - 8GB

##Minimum Specs Required (But not tested)

CPU  - i5
RAM  - 8GB
GPU  - Any gpu with a min of 6Gb memory and Cuda cores (RTX series preferred)
