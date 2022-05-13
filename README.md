swap ETH to stETH when it depege (>= 10% exchange rate)

instructions
- set your infura API KEY in a `.env` file `export WEB3_INFURA_PROJECT_ID=YOUR_INFURA_ID`
- run `brownie run/scripts --network mainnet`

note :  to exchange ETH to stETH in production, import your eth account `brownie accounts new (id)` and uncomment the exchange code in `run.py`