# Avax 4 Smart Contract Project
The objective of this contract is to be able to write a smart contrct to create our own ERC20 token and deploy it using Remix. This will be submitted for the AVAX PROOF intermediate course assessment. This will show how to implement some functions.

# Description
This smart contract allows the user to utilize or implement the functions **mint()**, **burn()**, **transfer()**, **adddDrink()**, and **buyDrink()** on their smart contracts.

# Content Overview
1. **Minting**: Only the owner can mint new Degen tokens using the `mint` function.
2. **Burning**: Degen tokens can be burned using the `burn` function.
3. **Adding Drinks**: The owner can add new drinks to the collection using the `addDrink` function.
4. **Buying Drinks**: Users can buy drinks using their Degen tokens with the `buyDrink` function. Purchased drinks are transferred to the user's inventory.
5. **User Inventory**: The contract maintains a mapping of each user's inventory, tracking the number of each drink they own.
6. **Transfering**: Allows any token holder to transfer tokens to another address.
7. **Checking Token Balance**: Allows the user to check the balance that has been transfer to the address.
   
# Getting Started
1. Open the source code in REMIX IDE.
2. Compile avax3.sol.
3. Connect your metamask through Inject Provider Environment.
4. Use the Deploy & Run Transactions tab.
5. Deploy and confirm the pop up metamask window.
6. Now you can use the features of the Deployed Contracts.
7. Check whether the transactions are recorded in the Snowtrace.

# Author
Mark Yohann J. Bantayao
