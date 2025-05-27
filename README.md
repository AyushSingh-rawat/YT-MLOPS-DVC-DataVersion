🚀 DVC Tutorial: Versioning Data with DVC and MLOps Best Practices
Welcome to the DVC Data Versioning Tutorial repository!
This project walks you through how to use DVC (Data Version Control) to manage datasets, pipelines, and model artifacts in an ML workflow — promoting reproducibility, collaboration, and modular ML development.

📁 Project Structure
.
├── data/            # Raw and processed datasets (DVC-tracked)
├── models/          # Saved models (DVC-tracked)
├── src/             # Scripts for training and evaluation
│   ├── train.py     
│   └── evaluate.py  # (optional)
├── dvc.yaml         # DVC pipeline configuration
├── params.yaml      # Training parameters
├── .dvc/            # DVC internals
├── .gitignore
└── README.md

🛠️ Getting Started
✅ Prerequisites
1) Python ≥ 3.7
2) Git
3) DVC

📥 Installation
1) Clone the repository
   git clone https://github.com/AyushSingh-rawat/YT-MLOPS-DVC-DataVersion.git
cd YT-MLOPS-DVC-DataVersion
2) Install Python dependencies
   pip install -r requirements.txt
3) Pull the tracked data and models
   dvc pull

⚙️ Core DVC Commands
| Command            | Description                            |
| ------------------ | -------------------------------------- |
| `dvc init`         | Initialize DVC in your Git repo        |
| `dvc add data/raw` | Track raw data with DVC                |
| `dvc run`          | Create a pipeline stage                |
| `dvc repro`        | Re-run the pipeline stages as needed   |
| `dvc push`         | Push data and models to remote storage |
| `dvc pull`         | Download data from DVC remote          |


🔄 ML Workflow Overview
1) Add and version raw data using DVC.
2) Define pipeline stages: preprocess → train → evaluate.
3) Update parameters in params.yaml as needed.
4) Use dvc repro to rerun the pipeline automatically.
5) Push everything to GitHub and share with your team.


🙋‍♂️ Author
Ayush Singh Rawat
