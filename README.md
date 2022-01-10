# Financial_Planner
This is a Jupyter notebook that creates two financial analysis tools which helps visualize a members current savings and whether they have enough reserves for an emergency fund additionally, by utilizing an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations, creates a financial planner for retirement which forecast the performance of a retirement portfolio in 30 years. 

---

## Technologies

This project leverages python 3.7 with the following packages:

```
Jupyter Notebook 
Pandas 
ALPACA
MCSimulation
```

---

## Installation Guide

Before running the application first install the following dependencies.
```
Install Anaconda Package
Pip intall Jupyter 
conda install -c anaconda requests
conda install -c jmcmurray json
pip install python-dotenv
pip install alpaca-trade-api
```

Verify the Installations 
```
pip list | grep -E "python-dotenv|alpaca-trade-api"
```
---

## Usage

To deturmine the new investment options, clone the repository and run **Jupyter Lab** in python: 

```python
Jupyter Lab
```
Jupyter lab should launch in a web browser, if it doesnt select one one of the hyperlinks it provides copy it and paste it into a web browser page.  

In order for this code to run correcly it requires you to get the Alpaca API and Secret Keys which can be made on 

* [ALPACA}(https://app.alpaca.markets/brokerage/new-account/overview) 

---

## Contributors

Brought to you by Olena Shemedyuk.

email: Olenashemedyuk@gmail.com

---

## License

MIT