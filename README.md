# Tokens Blacklist

# How to add new tokens to the blacklist
1. git clone https://github.com/dappradar/tokens-blacklist
2. Go to the `tokens` directory and select the relevant protocol
3. Edit `tokens.json` and add the token address to the `tokens` array (make sure the token is not already in the list)
4. Commit & Push the changes

# All Tokens
File `all-tokens.json` is generated automatically by GitHub Actions after new tokens are added to specific protocols.

# Where is this used?
This repository is used to remove scam tokens from user's portfolios at https://dappradar.com/hub/wallet
If you see a scam token in your wallet, please add it to the list or report it in our Telegram or Discord.
