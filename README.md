# PyChain
PyChain is a blockchain-based ledger system, complete with a user-friendly web interface. 
This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and verifies the integrity of the data in the ledger.

![pychain_ledger.jpg](pychain_ledger.jpg)

# Imports
Ensure all modules are installed and imported to ensure the project runs

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

# How to use
Run streamlit from an Anaconda Powershell, using the command:
``` 
streamlit run streamlit.py
```

The streamlit application should be opened on your default browser. Here you can input sender, receiver, and amount, then set the block difficulty. The transaction will then be added to a dataframe and displayed. Each block after being added can be inspected via the sidebar

After adding the block to the chain, the chain can then be verified.




