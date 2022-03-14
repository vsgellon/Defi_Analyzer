# Defi-DApps-Investment-Analyzer

DeFi, or Decentralized Finance  is a relatively new area of the crypto-currency world that aims to sustainably transform the financial services industry, primarily by eliminating financial intermediaries. 
This area involves two important terms which are DeFi centralized applications  which are applications related to borrowing lending, exchanges, payments) and which are based on the blockchain technology (the most popular is ethereum). This brings us to the second element which are the Defi Tokens, with a market capitalization of more than 2 billion, they are the ones who give this panoply of possible services, we can mention Maker, Uniswap, Aave...The principle is mainly based on Purchasing a DeFi coin transfers value to the related dApp.

Our DeFi projects aims to buil application to help the investors find the best project. 
Indeed, this project will try to provide an analysis by using Jupiter Notebook. 
The value of a coin is directly related to its control over liquidity. This can be measured by the following ratio: Market Cap/ Total Value Locked (TVL). Therefore, the investor will be able to use this tool to visualize TVL for all coins, Market Cap for all coins, and the comparison of the ratio between all the coins in order to see what is the best investment for him.

  ## Technologies

This project uses Anaconda and Jupyterlab with **Python 3.9** 

It incorporates the following 9 required dependencies. These dependencies include the folowing imports :

```
import os
import requests
import json
import pandas as pd
import hvplot.pandas
from defillama import DefiLlama
from requests import Request
from pycoingecko import CoinGeckoAPI
from datetime import datetime

%matplotlib inline

```





 ## Installation Guide
 It is necessary to install the different dependencies before launching the application.
 
 ### Install Anaconda 
 1. Install [Anaconda](https://www.anaconda.com/products/individual) 
 2. Open up GitBash(Windows) or Terminal(Mac)
 3. Type ```conda update conda```to update Conda
 4. Type ```conda update anaconda```to Update Anaconda
 5. Type ```conda -n dev python=3.9 anaconda```
 6. Type ```conda activate dev```to activate conda
 7. Install a dev environement kernel by typing ```python -m ipykernel install --user --name dev```
 8. Install a mode environement by typing ```conda install -c conda-forge nodejs```
 9. Launch JupyterLab by typing ```jupyter lab```
 
 
 
 ### Install the Request and Json Library 
 We will use the following Python modules and libraries to facilitate API requests:

 1. OS: The OS module comes under Python's standard utility models and provides functions for interacting with the computer's operating system. The OS module does          not require a separate download.
 2. Requests: The Python Requests library helps you access data via APIs.
 3. JSON: This library puts the response (that is, the data) from an API into a human-readable format.

 To install the Requests library, check that your development environment is active, and then run the following command:
  
  ```conda install -c anaconda requests```

 To install the JSON library, check that your development environment is active, and then run the following command:
   
   ```conda install -c jmcmurray json```

### Install Coingecko Api 

To install the Coingecko Api wrapper, check that your development environment is active, and then run the following command:

  ```pip install pycoingecko```

### Install DeFi Llama 

To install  DeFi Llama API client in python, check that your development environment is active, and then run the following command:

```pip install DeFiLlama```





  
 
 ## Usage
 
 You will need to clone the repo so that you can run the application:

``` https://github.com/locthai2002/Defi-DApps-Investment-Analyzer.git```

 ### Get the Total Liquidity
<img width="1440" alt="1" src="https://user-images.githubusercontent.com/96351609/155435909-e51d1274-1ac3-4a66-9eaa-df7fef19609f.png">
<img width="1440" alt="2" src="https://user-images.githubusercontent.com/96351609/155435934-1f19a6ae-ceeb-4747-9bf5-7508c90750e7.png">

 ### Analyze the differents TVL 
<img width="1418" alt="3" src="https://user-images.githubusercontent.com/96351609/155436053-0ebc6940-3e9e-4719-b1df-7179b27504c1.png">
<img width="1440" alt="4" src="https://user-images.githubusercontent.com/96351609/155436060-e974f3e8-2822-4455-a29e-e7c54d1ea1fe.png">

 ### Analyze the differents Market CAP
 <img width="1430" alt="5" src="https://user-images.githubusercontent.com/96351609/155436129-e40d36e6-3485-4411-ba10-ec067ad3a9c1.png">
<img width="1440" alt="6" src="https://user-images.githubusercontent.com/96351609/155436154-e91122a6-7e35-4fb8-a8d3-64cf8a13ae1c.png">

 ### Calculate the Market Cap/TVL Ratios
 <img width="1435" alt="7" src="https://user-images.githubusercontent.com/96351609/155436274-7907493c-2338-4ec1-970e-c6c71def4121.png">
<img width="1440" alt="8" src="https://user-images.githubusercontent.com/96351609/155436284-579796fb-b673-40a2-b363-6922b239c29b.png">

 ### Analyse the Historical Tokens Prices
 <img width="1440" alt="Capture d’écran 2022-02-23 à 4 22 17 PM" src="https://user-images.githubusercontent.com/96351609/155436357-9387ec9e-b888-4cc9-93fb-bfa33d84a632.png">
<img width="1440" alt="Capture d’écran 2022-02-23 à 4 22 59 PM" src="https://user-images.githubusercontent.com/96351609/155436375-b4a2149f-0f95-4fac-aedf-2773ede9a8c4.png">



 ## Contributor
 
Tim Tennyson

Loc Thai

Mohammed Amine Baite

Vic Gellon

 
 
