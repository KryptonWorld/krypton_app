##What is KryptonWorld app


##How to integrate to KryptonWorld
* You should know about [keth blockchain](https://github.com/KryptonWorld/keth_block_chain) first ,it is 100% compatible with Ethereum, provider is  http://keth.firewinggames.com:7545 
* The KryptonWorld app contains a dpp browser ,is is 100% compatible with Metamask, so your dapp can still use web3
* KryptonWorld app will add a token param after for your dppp url, you can use this token to get more info abount players.
* You must download KryptonWorld app [KryptonWorld](http://d.kxq.one/) or search KryptonWorld in GooglePlay
* You can add your app desc in games.json, your icon should add in icons dir ,then send a pull request 
* We will generate an appsecret for your app 
* you can get userinfo by 
    curl http://140.143.15.176/auth/decodetoken/:appkey/:token
  this userinfo format is json ,just like 
```javascript    
    {
      "nicheng":"mynicheng",
      "icode":"XQQQ",      //invite code
      "createts":111111111,  //create timestamp
      "unionid":"asdfasdfasdfasdfcxasdf"  //unique userid
    }
```



##
