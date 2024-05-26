# NFT Snapshot Tool ( support Telegram bot )

This tool assists projects in identifying the holders of an NFT collection to distribute project tokens to these holders via airdrop.

### HOW TO START
Install the necessary libraries:

`pip3 install -r requirements.txt`
Create the .env file following the template:

```
API_KEY_TONCENTER=

API_KEY_TELE=
```
### HOW TO RUN
#### CLI
`python3 NFT.py`
#### Telegram bot
`python3 bot.py`


### IMPORTANT
You must have the correct address of the NFT collection:
Steps to obtain:
- Assign the address of an NFT to Tonviewer (e.g.: EQBVQyaJyLI0vIRd7B1Py38Wee4lR3cvj_U59bgoV6C5-V8Y)
- Go to the method tab -> get_nft_data -> copy collection_address


