# PyChain_Ledger

I'm a fintech engineer who’s working at one of the five largest banks in the world. I was recently promoted to act as the lead developer on my decentralized finance team. My task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

---

## Technologies

This project leverages Python and its libraries for coding, VS Code as writing tool, and streamlit for user interaction.

---

## Open Guide

By running the streamlit, run `pychain.py` in terminal:

```
  1. Activate dev environment by: "conda activate dev"
  2. Run `pychain.py` by: "stremalit run pychain.py
```

---

## Usage

*Import the following libraries and dependencies:*

``` python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```
---

## Create and Modify a Record Data Class
Define a new Python data class named Record. 

```
@dataclass
class Record:
    sender : str
    receiver : str
    amount : float
```
---

## Add Relevant User Inputs to the Streamlit interface

```
sender = st.text_input("sender")
receiver = st.text_input("receiver")
amount = st.text_input("amount")
```

---

## Streamlit Result
![<streamlit>](<Image/streamlit.png>)

---

## Contributors

Feier Ou 

ffeierou1003@gmail.com 

---

## License

Feier Ou 