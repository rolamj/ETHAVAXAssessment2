# ETH+AVAX Assessment 2

## Overview

This is a project with a smart contract that works like an ATM that contains 4 functions and values of the functions is displayed in frontend app. Th functions are the following:

1. Connect your MetaMask wallet and check its balance.

2. Deposit and withdraw ETH in quantities of 1, 2, 3, and 5.

3. Multiply your balance by 2x, 3x, 5x, and 10x.

4. Change the owner of the contract.

## Getting Started

You can run the code locally, or you can use GitPod.

### Executing program

1. Clone the github repository: 

```bash
git clone https://github.com/rolamj/ETHAVAXAssessment2.git
```

2. Install the required dependencies

```bash
npm i
```

3. Open two additional terminals 
 
4. In the second terminal, type:

```bash
npx hardhat node
```
   
5. In the third terminal, type:

```bash
npx hardhat run --network localhost scripts/deploy.js
```
  
(6) Now, go back to the first terminal and type:

```bash
npm run dev
```

(7) Now, open the URL below in your browser and start interacting with the program

```bash
http://localhost:3000
```

## Author

- Michael John
  - GitHub: [@rolamj](https://github.com/rolamj)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---
