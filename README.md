# CTF Challenge

## Documentation

For PyTeal documentation, go to https://pyteal.readthedocs.io/en/stable/  
For Beaker documentation, go to https://algorand-devrel.github.io/beaker/html/index.html

## Usage

### Algokit Bootstrap

1. Create a new TestNet account using a 3-character prefix to help you identify your account on the leaderboard:
   `algokit task vanity-address <PREFIX>` where <PREFIX> is your 3-character identifier
   The response will contain your mnemonic
2. Fund your accoount using the TestNet Dispenser:
   `algokit dispenser login --ci`
3. Within the response, press Command + Click the URL link to open the Dispenser validation website
4. Follow the prompts, enter your email, check your spam folder for the verification code, complete the verification
5. You may close the Dispenser website after verification, which will return you to the CLI
6. The response will contain the ALGOKIT_DISPENSER_ACCESS_TOKEN
7. Bootstrap the project
   `algokit bootstrap all`
8. When prompted in the CLI, include the fields from #1 & #6
9. Register your account on the Google Form  

### Run Level 0 Challenge
1. `poetry run python3 level0.py`
2. Confirm your account is now on the [Leaderboard]()
