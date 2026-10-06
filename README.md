# Personal Banking Financial Analysis (Synthetic Data)
This project analyzes synthetic personal banking transactions to identify patterns and trends in income, expenditure, and spending behavior over time. The analysis explores financial activity at both annual and monthly levels, examines spending by entity, and uses data visualizations to communicate key findings. The project demonstrates an end-to-end data analytics workflow, from data preparation and exploration to analysis and presentation of insights.

## Technologies & Tools
- **Python & Pandas** – Data analysis and processing
- **Matplotlib, Plotly & Dash** – Data visualization and dashboard creation
- **Jupyter Notebook** – Development and analysis environment
- **Ollama** - Semantic summarisation using an LLM
- **fpdf2** - PDF creation using synthetic data
- **PDFPlumber** - Data extraction from PDFs

## Getting Started
Follow these steps to set up and run the notebooks on your local machine.

### Prerequisites
Before you begin, ensure you have Python 3.11.9 installed. 

### 1. Clone the Repository
Open your terminal or command prompt and run the following command to clone the project:
```bash
git clone https://github.com/mike-mayers/synthetic-banking-analysis.git
cd .\synthetic-banking-analysis\
```

### 2. Create a Virtual Environment (Recommended)
It is best practice to run Python scripts inside an isolated environment to prevent package conflicts.

* **On Windows:**
  ```bash
  python -m venv .venv
  .venv\Scripts\activate
  ```
* **On macOS and Linux:**
  ```bash
  python -m venv .venv
  source .venv/bin/activate
  ```

### 3. Install Dependencies
Install the required libraries listed in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 4. Register the Virtual Environment Kernel
To make sure your Jupyter environment can see the dependencies installed inside the virtual environment, link it as a kernel:
```bash
python -m ipykernel install --user --name=<venv-name> --display-name "Python (<your project name>)"
```

For example: 
```bash 
python -m ipykernel install --user --name=synthetic-analysis --display-name "Python (Synthetic Analysis)
```

### 5. Launching the Notebook
- Open any of the notebooks in your IDE (for example, VS Code).
- Once the notebook opens, ensure the correct kernel is selected. Look at the top-right corner. It should display **"Python (\<your project name>)"**. If it doesn't, click **Select Kernel** and choose the correct kernel from the dropdown.
- You can now run any of the notebooks.

## Data Privacy
The publicly available dataset is entirely synthetic and does not contain actual banking transactions or personally identifiable financial information.