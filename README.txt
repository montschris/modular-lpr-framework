User Guide – Thesis Code Execution
====================================

This document serves as the official user guide for running the codebase associated with our thesis.

Contents of the Code Package:
-----------------------------
- Main_Code.ipynb              : Main Jupyter Notebook containing scripts.
- data.yaml                    : YOLOv8 training configuration file.
- requirements.txt             : List of Python dependencies.
- weights/                     : Directory for model weights.
- data/                        : Directory for input data.
- outputs/                     : Destination for all generated results and logs.

System Requirements:
--------------------
- Python 3.8 or higher
- Jupyter Notebook or Google Colab
- GPU recommended for training (optional)

Installation Instructions:
--------------------------
1. Install Python from https://www.python.org/downloads/
2. (Optional) Install Anaconda from https://www.anaconda.com/ for environment management.
3. Install required dependencies by running:
   pip install -r requirements.txt

Running the Notebook:
---------------------
1. Open the Jupyter Notebook: test60 copy 14.ipynb
2. Ensure the following:
   - All referenced folders (e.g., weights/, data/) exist in the project root.
   - Paths in the notebook are updated appropriately if using a different directory structure.
3. Execute the cells sequentially.

Important Notes:
----------------
- Training and validation images are not included in the submission.
  Users intending to retrain the model should place their dataset inside the data/ directory
  and update 'data.yaml' accordingly.

- Pretrained model weights (e.g., YOLOv8, Real-ESRGAN) are not bundled. Please download and
  place them in the appropriate weights/ subdirectories as instructed in the notebook.

- The outputs/ directory will be populated with:
  - OCR results CSV
  - Evaluation metrics CSV
  - Debugging visuals

Contact Information:
--------------------
For additional guidance or troubleshooting, please contact the thesis authors directly.
