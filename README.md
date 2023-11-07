# Connect 3
![McSwap](https://connect.mcdegen.xyz/connect_3/icon-150.jpg)

(C3) Native Javascript Web3 Wallet Plugin.

## Supports:
* Phantom Browser Wallet
* Phantom Mobile Wallet
* Solflare Browser Wallet
* SolFlare Mobile Wallet
* Backpack Browser Wallet

## Automatic Deeplinks
If connecting from a mobile device browser, the user is redirected to the native mobile app when selecting Phantom or Solflare. If the user does not have the app installed, they are redirected to the wallets home website to download the mobile wallet app.

1. Make sure your metatag title and icon images are included in the head of your page.
```html
<meta property="og:image" content="https://connect.mcdegen.xyz/connect_3/icon-150.jpg">
<link rel="icon" href="https://connect.mcdegen.xyz/connect_3/icon-150.jpg" type="image/png">
<link rel="apple-touch-icon" href="https://connect.mcdegen.xyz/connect_3/icon-150.jpg" type="image/png">
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
[config/proxy.php](https://github.com/McDegens-DAO/Connect-3/blob/main/connect_3/example.html)
