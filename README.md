wechat-card
========================

Wechat Card API for NodeJS 

> **Do not support custom card and code, this part will be update in next version**

## Install

    npm install wechat-card

## Usage

```javascript
  var wxCard = require("wechat-card");

  wxCard.setConfig({
    appId: "YOUR APP ID",
    appSecret: "YOUR APP SECRET"

    // or config access token service
    // accessTokenService: "http://url"

  });

  wxCard.card.createCard(cardinfo, function(error, cardid) {
    // do something
  });
```

## Document

To be continued

## License

MIT