# TwitterGatedNFTDrop

This project is a web application that gates access to an NFT drop based on specific user actions on Twitter using Holaplex Hub's APIs.

## Features

- Authenticate users via Twitter
- Verify user actions on Twitter (like, retweet, quote-retweet, comment, or use a specific hashtag)
- Unlock access to an NFT drop if the user meets the specified criteria

## Prerequisites

- Python 3.8 or higher
- A Twitter Developer account with API keys and access tokens
- A Holaplex Hub account with API keys

## Installation

1. Clone the repository:

```
git clone https://github.com/juniorvish/TwitterGatedNFTDrop.git
```

2. Change to the project directory:

```
cd TwitterGatedNFTDrop
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Create a `config.py` file in the project root directory and add your Twitter API keys and Holaplex Hub API keys:

```python
twitterAPIKey = "your_twitter_api_key"
twitterAPISecret = "your_twitter_api_secret"
twitterAccessToken = "your_twitter_access_token"
twitterAccessTokenSecret = "your_twitter_access_token_secret"
hubAPIKey = "your_hub_api_key"
```

## Usage

1. Start the application:

```
python app.py
```

2. Open your web browser and navigate to `http://localhost:5000`.

3. Authenticate with your Twitter account and perform the required actions to unlock the NFT drop.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)