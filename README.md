# README: Architectural Flaw Detection in Civil Engineering Using GPT-4

## Overview
This repository hosts the resources and results associated with the paper:
**"Architectural Flaw Detection in Civil Engineering Using GPT-4"**

### Authors:
- **Saket Kumar**, The MathWorks Inc. - saketk@mathworks.com
- **Abul Ehtesham**, The Davey Tree Expert Company - abul.ehtesham@davey.com
- **Aditi Singh**, Department of Computer Science, Cleveland State University - a.singh22@csuohio.edu
- **Tala Talaei Khoei**, Khoury College of Computer Science, Roux Institute at Northeastern University - t.talaeikhoei@northeastern.edu

## Abstract
This project explores the application of Generative AI (GPT-4 Turbo Vision Model) to detect architectural flaws during the design phase, particularly focusing on missing doors and windows in floor plans. By leveraging AI, the study demonstrates enhanced accuracy in identifying structural issues, reducing costly revisions, and promoting sustainable practices.

Key highlights include:
- Identification of architectural flaws such as missing doors, windows, load-bearing issues, and material weaknesses.
- Assessment of AI's compliance with building codes and ergonomic standards.
- Integration of AI for sustainability and water management evaluations.
- Implementation of predictive maintenance and structural health monitoring.

The project supports the vision of improving the safety, sustainability, and efficiency of civil engineering projects.

## Dataset
The dataset used for this project consists of **100 annotated floor plans**. It is available publicly on GitHub:
[Dataset Link](https://github.com/asinghcsu/GPTCivilArchFlaw)

## Methodology
The project utilizes the GPT-4 Turbo vision model for architectural flaw detection. The methodology includes:
1. **Image Preparation**: Images are converted to Base64 for processing.
2. **Flaw Detection**: GPT-4 analyzes Base64 images to identify flaws related to missing doors and windows.
3. **Results Recording**: Flaws are recorded and analyzed with statistical metrics.
4. **Report Generation**: Confusion matrices, precision, recall, F1 scores, and ROC curves provide insights into model performance.

## System Architecture
The system architecture consists of four key steps:
1. Access images and convert them to Base64.
2. Send Base64 images to GPT-4 Turbo model for flaw detection.
3. Record results and classify flaws (e.g., missing doors or windows).
4. Generate statistical reports for research and analysis.

## Results
- **Overall Performance**:
  - Precision: 0.65
  - Recall: 0.57
  - F1 Score: 0.61

- **Door Detection**:
  - Precision: 0.33
  - Recall: 0.17
  - F1 Score: 0.23

- **Window Detection**:
  - Precision: 0.56
  - Recall: 0.68
  - F1 Score: 0.61

## Key Features
- Utilizes Generative AI for structural flaw detection.
- Supports compliance checks for building codes and ergonomic standards.
- Provides sustainability evaluations and predictive maintenance insights.

## Visualization
### Confusion Matrices and ROC Curves
- Figures included in the paper illustrate confusion matrices and ROC curves for flaw detection, missing doors, and missing windows.

## Citation
If you use this project in your research, please cite:

```
@misc{kumar2024architecturalflawdetectioncivil,
      title={Architectural Flaw Detection in Civil Engineering Using GPT-4}, 
      author={Saket Kumar and Abul Ehtesham and Aditi Singh and Tala Talaei Khoei},
      year={2024},
      eprint={2410.20036},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2410.20036}, 
}
```

## Getting Started
### Prerequisites
- Python 3.8+
- OpenAI API Key
- Libraries: `numpy`, `pandas`, `matplotlib`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/asinghcsu/GPTCivilArchFlaw.git
   cd GPTCivilArchFlaw
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Important Note
This repository shares the **annotated dataset, results, and analysis** discussed in the paper. 

## Future Work
- Integration of augmented reality (AR) for real-time flaw detection.
- Expansion of dataset to include diverse architectural designs.
- Enhancement of AI models to detect complex flaws, including seismic vulnerabilities and advanced compliance checks.

## Contact
For any questions or inquiries, please contact:
- Aditi Singh: a.singh22@csuohio.edu
