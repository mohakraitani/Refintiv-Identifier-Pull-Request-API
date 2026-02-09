# Refinitiv Identifier Conversion API

## Description

* This script is designed to link external datasets with Refinitiv/LSEG data by converting and matching securities using common financial identifiers.

## Table of Contents

- [Installation](#-installation)
- [API Key Requirement](#-apikey)
- [Supported Identifier Types](#-identifier-type)
- [Prerequisites](#-prerequisites)
- [License](#-license)
- [Usage Notes](#-usage-notes)
- [Limitations](#limitations)
- [Disclaimer](#-disclaimer)



## 🛠 Installation
Example for setting up the environment (we strongly recommend creating a dedicated virtual environment)
git clone https://github.com/mohakraitani/Refinitiv-Identifier-Conversion-API.git
cd Refinitiv-Identifier-Conversion-API
pip install 


## 🔑 API Key Requirement

Before running the script, you must generate an API key from Refinitiv / LSEG.

Steps to generate an API key:

* Open the Refinitiv Workspace.

* In the search bar, type APPKEY (App Key Generator).

* Select EDP API.

* Create a new API key and assign it a name of your choice.

* Copy and securely store the generated API key.
  

## 🔄 Supported Identifier Types

The script supports conversion between the following identifier formats:

['RIC', 'ISIN', 'CUSIP', 'SEDOL', 'ticker', 'lipperID', 'IMO', 'OAPermID']


* All values passed to the to_symbol parameter must belong to the list above.

* All values passed to the from_symbol_type parameter must also belong to the same list.
  

## 🧩 Prerequisites

* Valid Refinitiv/LSEG account with API access

* Active EDP API key



(Optional but recommended)

* Python 3.8+

* Required Python libraries installed (if applicable)


## ▶️ Usage Notes

* Ensure that the identifiers provided are valid and correctly formatted.

* The script performs identifier conversion only; it does not validate firm fundamentals or market data.

* Missing or unsupported identifiers may return empty or null results.
  

## 📝 License
This project is licensed under the MIT License.


## 🛑 Limitations

* API rate limits apply as per Refinitiv/LSEG policy.

* Identifier coverage depends on Refinitiv’s database availability.

 ## ▶️ Disclaimer

- This repository is an independent, personal open-source project and is **not affiliated with, endorsed by, or officially supported by Refinitiv, LSEG, or the author’s institution**.
- The code is provided for general use only and comes **without any warranty or guarantees**.
- Users are responsible for ensuring compliance with applicable **Refinitiv/LSEG data usage and licensing terms**.


