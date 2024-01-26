## Connect your app to a smart contract on the XRPL EVM Sidechain

You will need to deploy a smart contract. You can do so by following this tutorial:

https://github.com/XRPL-Commons/xrpl-commons-january-2024/tree/main/apps/lending-contract

Once you have a smart contract address on the EVM sidechain, you can update the contractAddress variable in `script.js` with this information.


## serve this with your prefered server

If you have node you can use serve:

https://www.npmjs.com/package/serve

```npm install --global serve```

then navigate to the root of this project

```serve```