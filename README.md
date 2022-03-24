# MagicToken Staking Contract

TestNet used: Kovan

Token 1 --> MAGIC Token

    address: 0xD19f28dbE3FFd95b7ed8F4fA062DDcB395d3FdaA
    Total supply: 100000000000000000000000
    Token Name: MAGIC Token
    Token Symbol: MAGIC
    Decimalsl: 18
    Kovan Link: https://kovan.etherscan.io/address/0xd19f28dbe3ffd95b7ed8f4fa062ddcb395d3fdaa#code

Token 2 --> RMAGIC Token
    
    address: 0x045d6BCca7432b06665311dA17824f4acF0AE872
    Total supply: 100000000000000000000000
    Token Name: Magic Reward Token
    Token Symbol: RMAGIC
    Decimalsl: 18
    Kovan Link: https://kovan.etherscan.io/address/0x045d6bcca7432b06665311da17824f4acf0ae872#code

Staking --> Reward Token Pool
    
    address: 0x71dc4cf37c576dcf5aa87f630deb3eeea3454a7f
    Kovan Link: https://kovan.etherscan.io/address/0x71dc4cf37c576dcf5aa87f630deb3eeea3454a7f#code

Methods:
    1. Stake
    2. Unstake
    3. Issue Token (OWNER only)
    
Process to work:

   1. First deploy all the contracts

   //10000 -> 5000(or any amount)
   2. Transfer all the rewards token to stake contract(address)

   //10000 -> 2000
   3. Transfer some tokens from main token to USER1

   4. Copy the stake contract address and paste it & approve the staking value in main token contract approve function from the staking USER1

   5. Stake few amount of tokens from USER1 in STAKING contact

   6. Switch to MAIN user(owner) and issue tokens in staking contract

   7. Now unstake all the tokens from the respective USER accounts

   8. Now check the balance in Main and REWARD tokens
