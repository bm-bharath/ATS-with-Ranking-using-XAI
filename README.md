# ATS-with-Ranking-using-XAI
# Writing the requirements.txt file
requirements_path = '/mnt/data/requirements.txt'

# Standardizing library names where possible for `requirements.txt`
requirements = [
    "PyPDF2",
    "gensim",
    "lime",
    "numpy",
    "pandas",
    "panel",
    "scikit-learn"
]

with open(requirements_path, 'w') as req_file:
    req_file.write("\n".join(requirements))

# Drafting the README.md file
readme_path = '/mnt/data/README.md'
readme_content = """
# Project Title

This project processes and analyzes text using machine learning techniques. It includes the use of Python libraries for text vectorization, classification, and other analyses.

## Requirements

Install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
