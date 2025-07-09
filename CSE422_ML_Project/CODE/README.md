# Setup Instructions for Jupyter Notebook

## Important Notes for Running the Notebook

### Data Path Configuration
The notebook currently contains hardcoded paths that need to be updated for local use:

**Current path in notebook:**
```python
path = '/content/drive/MyDrive/422 project/heart_desease_data.csv'
```

**For local use, update to:**
```python
path = '../DATA/heart_disease_data.csv'
```

### Quick Setup Steps

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Start Jupyter:**
   ```bash
   jupyter notebook
   ```

3. **Open the notebook:**
   Navigate to `CSE422_ML_Project/CODE/heart_disease_prediction.ipynb`

4. **Update the data path:**
   Change the file path in the data loading cell to use the relative path shown above.

5. **Remove Google Drive mounting:**
   Comment out or remove any Google Colab specific code like:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

### Expected Workflow
1. Data loading and exploration
2. Data preprocessing and cleaning
3. Model training with multiple algorithms
4. Performance evaluation and comparison
5. Results visualization and analysis

The notebook should run smoothly after making these path adjustments.