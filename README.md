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

These two commands are used to create and deploy your own subnet on the avalance CLI. 
# Getting Output
Once your Subnet has been created and deployed. u will be provided with the details of the subnet on the terminal. You may use these details and create new network on the metamask wallet which u can use for operating on your subnet.

You may then copy paste the code provided and deplou it on remix. Remember to deploy it on the Injected provided(metamask) server. Then you can connect your metamask wallet to remix and run any fucntions on the remix application and interact with your subnet.

## Authors

Mokshith P  
Email: mokshithlucky06@gmail.com

## License

This smart contract is licensed under the [MIT License](LICENSE).
