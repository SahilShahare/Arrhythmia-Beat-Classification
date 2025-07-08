# Arrhythmia Beat Classification

This project involves classifying different types of arrhythmic heartbeats using ECG data for multiple datasets.

**Original Paper**: [Ye C, Coimbra MT, Vijaya Kumar BK. Arrhythmia detection and classification using morphological and dynamic features of ECG signals. Annu Int Conf IEEE Eng Med Biol Soc. 2010;2010:1918-21. doi: 10.1109/IEMBS.2010.5627645. PMID: 21097000.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5627645)


## 🔧 Configuration

Replace dummy paths in `paths.json` file in the project directory with paths to the datasets on your system:

```json
{
    "mit-bih-arrhythmia": "/absolute/path/to/mit-bih-arrhythmia",
    "incart": "/absolute/path/to/incartdb",
    "mit-bih-supra-ventricular": "/absolute/path/to/svdb"
}
```
## ⚙️ Requirements & Installation
```
Python 3.12.8
wfdb 4.3.0
scipy 1.16.0
numpy 2.2.1
Pywavelets 1.8.0
scikit-learn 1.7.0
seaborn 0.13.2
matplotlib 3.10.3
pandas 2.3.0
joblib 1.5.1
```
Ensure ```python >= 3.12.8``` is installed. 

```
conda activate <your env>
pip install -r requirements.txt
```
## 💡 Tips
* Refer [here](https://github.com/SahilShahare/Nirvana-Setup) for Nirvana and Jupyter Notebook Setup on VS-Code.