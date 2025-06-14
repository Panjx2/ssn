# EKG Anomaly Detection

This repository contains a Jupyter notebook for detecting anomalies in EKG signals using a RandomForest classifier. The notebook downloads training and validation data, extracts custom features and trains a model with limited resources.

## Usage

Install the required packages and open the notebook:

```bash
pip install -r requirements.txt
jupyter notebook 3_wykrywanie_zaburzen_sygnalu_ekg.ipynb
```

The notebook trains the model and evaluates it on a validation set. The final cell saves the trained model when `FINAL_EVALUATION_MODE` is enabled.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
