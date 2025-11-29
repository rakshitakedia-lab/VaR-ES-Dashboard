# **Value-at-Risk (VaR) & Expected Shortfall (ES) Dashboard**

## **Overview**
This Python project calculates **Value-at-Risk (VaR)** and **Expected Shortfall (ES)** for equity portfolios or individual stocks. It implements:

- **Historical Simulation**  
- **Parametric Normal Distribution**  
- **Parametric t-Distribution**

The dashboard automatically fetches historical price data, computes daily returns, visualizes tail losses, and optionally generates a **PDF risk report**.



## **Features**

1. **Automatic Data Fetching**  
   Pulls historical price data for any ticker (e.g., **AAPL**, **NIFTY50**).

2. **Return Calculation**  
   Computes **daily log returns**.

3. **VaR Calculation**  
   - **Historical Simulation**  
   - **Parametric Normal Distribution**  
   - **Parametric t-Distribution**

4. **Expected Shortfall (ES)**  
   Computes **average losses beyond VaR thresholds**.

5. **Visualizations**  
   - **Return histogram** with **VaR & ES lines**  
   - **Rolling VaR time series**  
   - **Tail loss highlights**

## **How To Run**
1. **Clone the Repository**
- **git clone https://github.com/rakshitakedia-lab/VaR-ES-Dashboard.git**
- **cd VaR-ES-Dashboard**

2. **Install dependencies**
- **pip install -r requirements/requirements.txt**

