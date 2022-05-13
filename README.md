## swap ETH to stETH when it de-peg (>= 10% exchange rate) on Curve.fi

#### Instructions:
- set your infura API KEY in a `.env` file `export WEB3_INFURA_PROJECT_ID=YOUR_INFURA_ID`
- run `brownie scripts/run.py --network mainnet`

###### Note :  to exchange ETH to stETH in production, import your eth account `brownie accounts new (id)` and uncomment the exchange code in `run.py`
