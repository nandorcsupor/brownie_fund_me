# brownie_fund_me

Deploys a contract that can be funded by anyone, but only the owner can withdraw the money.


Make .env file and fill out these parameters:

export PRIVATE_KEY =
export WEB3_INFURA_PROJECT_ID =
export ETHERSCAN_TOKEN =


run : 
    - cd scripts    
    - brownie run deploy.py

