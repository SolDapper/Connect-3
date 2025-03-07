# Connect 3

Native Javascript Web3 Wallet Plugin.

This plugin provides a basic Solana Web3 wallet connection using native javascript only.

FreeSolGamesDev created a nice jquery derivation of Connect-3 with more features that you can find on jsfiddle [here](https://jsfiddle.net/FreeSolGamesDev/7a4yvx23/281/).

## Supported Wallets
* Phantom, Solflare, Backpack

## Basic Installation

1. Make sure your metatag title and icon images are included in the head of your page.
```html
<title>Connect 3</title>
<meta name="description" content="Native Javascript Web3 Wallet Plugin." />
<meta property="og:image" content="https://website.com/icon-150.jpg">
<link rel="icon" href="https://website.com/icon-150.jpg" type="image/png">
<link rel="apple-touch-icon" href="https://website.com/icon-150.jpg" type="image/png">
```

2. Add the Connect 3 stylesheet in the head of your page.
```html
<link rel="stylesheet" href="connect_3.css">
```

3. Add Connect and Disconnect buttons anywhere in the body of the page.
* Element class for Connect buttons = connect_3_button
* Element class for Disconnect buttons = disconnect_3_button
```html
<button class="connect_3_button">Connect</button>
<button class="disconnect_3_button">Disconnect</button>
```

4. Add the Connect 3 container and script immediately before the closing body tag.
```html
<div id="connect_3"></div>
<script src="connect_3.js"></script>
```

Please see the source code of the example.html file.
[connect_3/example.html](https://github.com/McDegens-DAO/Connect-3/blob/main/connect_3/example.html)
