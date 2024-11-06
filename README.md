# Teneo Node Extension
Teneo Community Node on CLI version

# Warning
All risks are borne by the user.

# Registration
Download this [extension](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm) first

Signup and Use Referral Code: `Pdzvm` to get 2.500 Extra Teneo Points.

## About Proxy

Website with the cheapest proxy price $1/GB [Here](https://dataimpulse.com/?aff=65610)

You can add proxy in the `config.json` file, and then proxy format is as follows:
```
"protocol://user:password@hostname:port"
```
Example:
```
"proxy": "http://username:password@host:port"
```
## How to get userID
1. Open DevTools on Extension (right-click on the page and select "Inspect").
2. Go to the "Application" tab, then "Local Storage", and choose `sb-ikknngrgxuxgjhplbpey-auth-token`
3. Find ID and copy the value

## How to Running
Clone this repo
```
git clone https://github.com/Aethereal-Collective/teneo
```
Install Dependencies
```
npm install
```
Change your UserID on `config.json`

Run the script
```
node main.js
```
