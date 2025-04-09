**Mining Leaderboards**

https://weso-mining-leaderboard.streamlit.app

https://base-mining-leaderboard.streamlit.app

---

**PoW Miner Instructions**

1)      Download the miner from: https://github.com/LunaClassicDAO/WESO_BASE_MINER

-   For Linux: weso_base_pow_miner_v01

-   For Windows: weso_base_pow_miner_v01.exe

-   For MacOS: 
     - (Intel) weso_base_pow_miner_mac_amd64_v01 or (Apple Silicone) weso_base_pow_miner_mac_arm64_v01 
     - (Must place in a folder called POW_MINER)

2)      Change permissions to executable via commandline:
-   For Linux:
     -   chmod +x ./weso_base_pow_miner_v01
-   For Windows:
     -   N/A
-   For MacOS:
     -  chmod +x /path_to_folder/POW_MINER/base_miner_mac_arm64_v01 or
     -  chmod +x /path_to_folder/POW_MINER/base_miner_mac_amd64_v01

3)      Start miner from the commandline (in same directory as file):

-   For Linux:
     - ./weso_base_pow_miner_v01
-   For Windows:
     - weso_base_pow_miner_v01.exe
-   For MacOS:
     - ./base_miner_mac_arm64_v01

4) Select token to mine

![](/images/token.jpg)

5)      Add wallet address with option 2

![](/images/add.jpg)

6)      Select the wallet with option 1

![](/images/wallet.jpg)

7)      Select number of CPU treads to use:  

![](/images/threads.jpg)

---
---

**Warning:** <font color="red"> **DO NOT use the same wallet address for multiple miners.** </font>Doing so may activate the anti-cheat system (due to exceeding the rate limit) and you will  <font color="red">**NOT earn rewards!** </font>

![](/images/exceeded.jpg)

---
---

**Command line options:**

<font color="red">**Not all CPUs support all options**</font>

AES hashing

-   \-aes\_hashes hw (default)

-   \-aes\_hashes sw (slower)

Execution mode

-   \-exec\_mode vm (default)

-   \-exec\_mode jit (faster)

Pages Size

-   \- mem\_pages small (default)

-   \-mem\_pages large (faster)

Memory Size

-   \- mem\_size full (default)

- \- mem\_size lite (slower)

---
---

Credit goes to Bill for providing the instructions on the MacOS version
