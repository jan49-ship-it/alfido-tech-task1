# Heart Disease Prediction API

## Overview
This project deploys a Heart Disease Prediction model using Flask and Docker.

## Files
- train_model.ipynb
- heart.csv
- model.pkl
- app.py
- requirements.txt
- Dockerfile
- sample_request.json

## Install

```bash
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

## API Endpoint

POST `/predict`

### Sample Request

```json
{
  "features": [63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]
}
```

### Sample Response

```json
{
  "prediction": 1
}
```
