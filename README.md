# Cryptocurrency Payment

This service is used to send cryptocurrency payments to fintech professionals from a list of candidate considered for hiring them.

---

## Technologies:

- [streamlit](https://pypi.org/project/streamlit/) - for creating & sharing customized beautiful web apps
- [Web3.py](https://pypi.org/project/web3/) - python library helps in connecting to & performing operations on Ethereum-based blockchains
- [ethereum-tester](https://pypi.org/project/ethereum-tester/) - provides access to the tools we’ll use to test Ethereum-based applications
- [mnemonic](https://pypi.org/project/mnemonic/) - for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard
- [bip44](https://pypi.org/project/bip44/) - for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard
- [Ganache](https://pypi.org/project/ganache/) - A program that allows to quickly set up a local blockchain, can be used to test & develop smart contracts


---


## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install streamlit
  pip install ethereum-tester
  pip install mnemonic
  pip install bip44

```

---

## Usage

To view the files, clone the repository using "git clone <link>" in the [repository directory](https://github.com/Summi-Khanna/Challenge-19.git)

Run the streamlit application by using the below command in terminal:
`streamlit run fintech_finder.py`

To run this program insert your mnemonic from Ganache suite in the sample.env file and then rename file to (dot)env and save.

`MNEMONIC='xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx'`

--- 

## Visualization

- Hiring Lane for 1 hour and making payment
![image-1](https://github.com/Summi-Khanna/Challenge-19/blob/main/Images/Image-1.png)

- Sending transaction with Ethereum account information
![image-2](https://github.com/Summi-Khanna/Challenge-19/blob/main/Images/image-2.png)
![image-3](https://github.com/Summi-Khanna/Challenge-19/blob/main/Images/image-3.png)


---


## Contributors
 
Summi Khanna  
Email : sam.summo2812@gmail.com <br>
LinkedIn : https://www.linkedin.com/in/summi-khanna-004a60187/

---

## License

MIT License

Copyright (c) 2021 Summi Khanna

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
