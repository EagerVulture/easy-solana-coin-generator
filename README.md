# SOLANA MEMECOIN TOKEN CREATOR

Create a **Solana Memecoin Token under 2 minutes** with **MINT DISABLE, RENOUNCE OWNERSHIP, ADD LIQUIDITY, BURN, RUGPULL** functionalities & extremely **CHEAPER** than web-based for-profit tools. The rugpull functionality guarantees that your invested SOL will return from the LP withdraw along with Profits. Currently being used by many Devs for creating tokens by the minute & pulling profits within seconds of launch.

# DEMO VIDEO OF TOOL IN ACTION:
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/JKis3ivf5wk/0.jpg)](https://www.youtube.com/watch?v=JKis3ivf5wk)
<br></br>
# GETTING STARTED:

To get started with creating and minting SPL tokens, follow these steps:
1. Clone this repository to your local machine using below command:

   ```bash
   git clone https://github.com/EagerVulture/easy-solana-coin-generator.git
   ```
   Or alternatively download the .zip & extract to your local machine.

2. Navigate to the project directory using below command:

   ```bash
   cd easy-solana-coin-generator
   ```
3. Make sure you have node.js installed on your system, if not you can download it from the below link:

   https://nodejs.org/en/download

   **You can also follow the below link for the installation process:**

   https://www.geeksforgeeks.org/installation-of-node-js-on-windows/

4. Install the project dependencies using below command:

   ```bash
   npm install
   ```
5. Edit the .env.copy file & add the required fields. If you have a custom RPC, you can replace it with yours.

    ``PRIVATE_KEY=YourPrivateKeyHere``

    ``RPC_ENDPOINT=Keep it default or add your RPC``
6. Rename .env.copy file to .env
   
   **You can do a manual rename or use below command:**

   ```bash
   mv .env.copy .env
   ```
8. Create your token:

   Run the following command to start the token creation process:

   ```bash
   npm start
   ```
9. Fill all the prompts:

   The token creator will prompt you with questions to configure your token, such as token decimals, total supply, token name, symbol, image URL, royalty percentage, mint, liquidity, burn, etc.

11. Token Creation:

   - The script will create and send the mint token transaction, etc.
   - You will receive updates on the transaction's success, transaction hash, and links to view the transaction on Solana Explorer and Solana BirdEye (if on the mainnet).

11. **Congratulations! You've successfully created your own Memecoin token on the Solana blockchain.**

## IMPORTANT INFORMATION:

- **Use the Rugpull feature to pull the liquidity in the time given during the prompts. Ideal value would be 120-300s (2-5mins). If you don't wish to rugpull, then set the value as 0.**

- **Make sure you are on the mainnet while creating the token & have enough SOL (Min 2 SOL) to cover the fee for token creation, LP addition, Mint, etc. Else, you may lose the transaction fee for the already completed transactions & might get error as your wallet doesn't have enough balance to proceed further. Setting value to 0 for Mint, Renounced, Burn will not include any charges.** 

- **Cost of adding the Liquidity is upon the user, you can choose to add 5 SOL or 50 SOL, it's up to you. Recommended min LP size is 5 SOL for 50-80% supply. Make sure to have equivalent SOL in your wallet, else the transaction will fail.**

- **You can set royalty to get tax % on transactions.**

- **This project is designed for local use, and your wallet's secret key is not stored or transmitted over the internet. It's important to keep your wallet's secret key secure and never share it with anyone. The token creation process is entirely local, and your wallet's secret key is only used for transaction signing within the script.**

## USEFUL TIPS:

**If you face an error during npm start, try the below command:**

```bash
   npm install --save @solana/web3.js
   ```

# DISCLAIMER

**THIS IS FOR EDUCATIONAL PURPOSES ONLY, NFA, DYOR. I'M NOT RESPONSIBLE FOR ANY LOSS YOU MAKE FROM THIS SOFTWARE.**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
