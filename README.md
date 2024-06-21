# binance_trading_dashboard
A Streamlit dashboard that uses Binance API data

## Run Dashboard
Clone the repo
```console
git clone https://github.com/zereaykut/binance_trading_dashboard
cd binance_trading_dashboard
```

Create python environment
```shell
python -m venv env
```

Activate environment in Mac/Linux 
```console
source env/bin/activate
```

Activate environment in Windows 
```console
env\Scripts\activate
```

Install required packages
```console
pip install -r requirements.txt
```

Add your binance info to config.json
```json
{
  "API_KEY": "your_binance_api_key",
  "SECRET_KEY": "your_binance_api_secret_key"
}
```

Get dashboard data
```console
python binance_crypto_data.py
```

Run dashboard
```console
streamlit run binance_crypto_dashboard.py
```
