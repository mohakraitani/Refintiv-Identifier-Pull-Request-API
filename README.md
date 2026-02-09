# Refintiv-Identifier-Pull-Request-API

📌 Overview

This script is designed to link external datasets with Refinitiv/LSEG data by converting and matching securities using common financial identifiers.

🔑 API Key Requirement

Before running the script, you must generate an API key from Refinitiv / LSEG.

Steps to generate an API key:

           1. Open the Refinitiv Workspace.

           2. In the search bar, type APPKEY (App Key Generator).

           3. Select EDP API.

           4. Create a new API key and assign it a name of your choice.

Copy and securely store the generated API key.

🔄 Supported Identifier Types

The script supports conversion between the following identifier formats:

['RIC', 'ISIN', 'CUSIP', 'SEDOL', 'ticker', 'lipperID', 'IMO', 'OAPermID']


* All values passed to the to_symbol parameter must belong to the list above.

* All values passed to the from_symbol_type parameter must also belong to the same list.

🧩 Prerequisites

Valid Refinitiv/LSEG account with API access

Active EDP API key

Internet connection

(Optional but recommended)

Python 3.8+

Required Python libraries installed (if applicable)

▶️ Usage Notes

Ensure that the identifiers provided are valid and correctly formatted.

The script performs identifier conversion only; it does not validate firm fundamentals or market data.

Missing or unsupported identifiers may return empty or null results.

🛑 Limitations

API rate limits apply as per Refinitiv/LSEG policy.

Identifier coverage depends on Refinitiv’s database availability.
