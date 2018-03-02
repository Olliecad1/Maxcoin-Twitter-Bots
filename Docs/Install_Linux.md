# Linux Install Guide or Raspberry Pi


## First of you need to make some api keys for twitter use this for [reference](https://themepacific.com/how-to-generate-api-key-consumer-token-access-key-for-twitter-oauth/994/)

## Step 1

Download the Python Scripts

```
git clone https://github.com/Olliecad1/Maxcoin-Twitter-Bots/
```

## Step 2

Change Directory into Maxcoin-Twitter-Bots/Scripts/

```
cd Maxcoin-Twitter-Bots/Scripts/
```

## Step 3

Open the file to add your twitter api keys to the script, i like to use nano editor

```
sudo nano MaxcoinPrice.py

```

Go down to where it says in the file
```
## Setting these as variables will make them easier for future edits
app_key =  ''
app_secret = ''
oauth_token = ''
oauth_token_secret = ''
```
and add your keys in there


## Step 4


Run the script

```
sudo python MaxcoinPrice.py
```





