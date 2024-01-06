# Building Your DeFi Empire  
In the project, we will learn how to set up our own EVM Subnet on Avalanche, which is an excellent starting point for building your DeFi Kingdom.
# Description
In the document u you will find a detailed procedure on how to create your own custom Subnet and Deploy it using the Avalanche CLI. We then connect this subnet to your MetaMask wallet by giving the correct RPC URl and the other details. Once the subnet is created we can use it to dploy two smart contracts on remix and interact with it.
Note that, the Avalanche CLI does not get installed on some networks, as the network provider might have blocked it.
To access and run your Solana code on remix u may use this link to open Remix : https://remix.ethereum.org/ .

# Getting Started
To get started with, you will have to install the Avalanche CLI on to your local system on linux(u can also install and run it using Ubuntu) , u may use this link for installation: https://docs.avax.network/tooling/cli-guides/install-avalanche-cli . Once installed by following the guidlines in the webiste u will have to create your own custom subnet by executing the following commands on your terminal:

``` avalanche subnet create mySubnet ```

```avalanche subnet deploy mySubnet```

In these two commands u are creating and deploying your own subnet. Once deployed the details of your subnet will be created and then u can copy paste the code provided in the repository on remix which allows u to intereact wiht the subnet by connecting your metamask wallet to it.

## Authors

Mokshith P  
Email: mokshithlucky06@gmail.com

## License

This smart contract is licensed under the [MIT License](LICENSE).
