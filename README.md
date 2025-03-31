 Revolt Trading AI

**Revolt Trading** is an AI-powered autonomous trading system designed to help you achieve financial freedom. It combines **XGBoost** and **TensorFlow** to detect opportunities and execute real trades based on intelligent decision-making.

> ⚡ A revolutionary tool for smart traders looking to automate, grow, and dominate the markets.

---

## 🔧 Key Features

- 🤖 **Hybrid AI Models**: Uses both XGBoost and Deep Learning (TensorFlow).
- 🔁 **Auto-Reinvestment**: Reinvests profits daily to compound capital.
- ⚡ **Asynchronous Trading Engine**: Fast, scalable and non-blocking.
- 📊 **Capital Growth Simulator**: Forecast your financial trajectory.
- 🔐 **Secure Integration**: Works with Kraken API (REST for trading, WebSocket for price feed).
- 🧠 **Learning System**: Automatically adjusts itself over time (future module).
- 📈 **Visual Dashboard**: Monitor performance and signals (coming soon).

---

## 📁 Project Structure

RevoltTradingAI/
├── main.py                    # Asynchronous bot loop
├── .env.example               # Environment variable template
├── requirements.txt           # Python dependencies
├── README.md                  # Project overview and instructions
│
├── revolt_trading/
│   ├── config.py              # Environment and model config
│   ├── predictor.py           # Hybrid prediction engine
│   ├── executor.py            # Order execution via Kraken API
│   ├── reinvestment.py        # Auto-capital adjustment logic
│   ├── logger.py              # Logging system (console + file)
│   ├── simulator.py           # Compounding growth simulation
│   └── __init__.py
│
├── models/                    # Trained models (XGBoost + TensorFlow)
│   ├── model_xgb.json
│   └── model_tf.h5
│
├── logs/                      # Prediction and execution logs
│   ├── operaciones.log
│   └── predicciones.log
│
├── data/                      # Capital state, simulation outputs, etc.
│   └── capital_state.json
│
├── branding/                  # Logos and brand assets
│   ├── revolt_logo.png
│   └── revolt_logo.gif
│
└── dashboard/                 # Streamlit dashboard (in progress)
    └── app.py
