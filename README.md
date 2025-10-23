Description: Daily gold price time series (2015–2025) with Date and price fields suitable for next day Close prediction; standard OHLC columns may be present, Volume may be absent; Close is the target; chronological split and scaler fit on train.
Instances: Values are in INR or USD depending on the file; percentage metrics (MAPE) allow scale free comparison.”.
Applicability: canonical next day Close forecasting; indicators (SMA/EMA, RSI, ATR, Bollinger) optional; use the same window length as equities for comparability.
Attributes: Date, Open, High, Low, Close; some files include Bid/Ask or Volume—if Volume is missing, drop it from features.
