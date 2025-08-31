ales Trend Predictor

Predict future sales using a custom PyTorch neural network with lag and time-based features.

Features

Neural network built from scratch (no pre-trained models)

Manual hyperparameter tuning

Saves the best-performing model automatically

Works on Google Colab and local Python environments

Quick Start
git clone https://github.com/your-username/sales-trend-predictor.git
cd sales-trend-predictor
python3 -m venv venv
source venv/bin/activate      # Mac/Linux
pip install -r requirements.txt
python src/main.py            # Run training & evaluation

Best Model

Saved as: models/best_sales_model.pth

Load later:

model.load_state_dict(torch.load("models/best_sales_model.pth"))
model.eval()

Tech Stack

Python 3.10+, PyTorch, Pandas, Scikit-learn, Matplotlib

Future Improvements

Early stopping

More lag features (Lag_60, Lag_90)

Seasonal trend models (LSTM/GRU)

Web dashboard for predictions
