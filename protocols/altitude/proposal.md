# Protocol Summary
Altitude (PWDR) is an evolutionary cryptocurrency that is pushing the limits of DeFi by combining yield farming, flash loans, and community governance. Typical DeFi tokens tend to benefit whales that get in early, where few can profit and the many are left holding the bag. We aim to change that paradigm so everyone can secure value through the combination of sustainable high-APR farming, flash loans for ongoing long-term value, and a cyclical mechanism to retain value through platform fees, locked liquidity, and rewards for stakers.

# Protocol Usage
*Explain how users use your protocol, where the funds would be at risk and where the coverage is specifically desired.*

- Yield Farming: PWDR is farmed by staking tokens in the SLOPES. Yield from the
slopes is earned in BOTH the staked token and PWDR. During the initial
distribution epoch, PWDR tokens are rewarded to stakers every block using a
fixed APR of 800%. Future epochs change the fixed APR of the slopes per the
PWDR Epoch Schedule. All slopes only require a single token so there is NO
RISK of impermanent loss (IL).
- Flash Loans: Developers can easily use Altitude's flash loans to borrow against
the Total Value Locked (TVL) in the slopes at a market leading rate. Fees collected
from these flash loans are used to reward stakers in the slopes.
- Sustainable Tokenomics: PWDR is released in Epochs with distinct
Accumulation and Distribution phases. This cyclical emission strategy is designed
to combat inflation and preserve PWDR value.
- Loyalty Points: To stay competitive in the current market, Flash Loans must be
competitively priced. Altitude implements a tiered loyalty system where
discounts are provided to developers who use the platform frequently, providing
an increasingly cheaper source of Flash Loans.
- NFT Item Boosts: Exclusive NFT series releases that provide boosts for Altitude
Slopes and Flash Loan activities.
- Governance: Extendable governance model with a role-based implementation.
Initially, necessary Altitude ecosystem roles set up to control access. In the future,
governance will extend to accommodate public voting contracts and quorums.
- Upgradeability: All Altitude contracts built with upgradeable contract logic,
allowing the Altitude Ecosystem to evolve to meet the arising needs of the
network participants.

Areas where funds could be exposed to risk: During flash loans and any currently unknown exploits in yield farming


# Protocol Stats
* Protocol age: **`0 months`**
* Protocol TVL: **`$0`**
* Collaterals in Protocol: **`ETH,wETH,DAI,wBTC,USDT,USDC .`**

# Protocol Risk

### Risk Details & Audits
*Detail the risks and organization of your protocol.
Please attach a link to audits if they have been received.*

Contract Protocols:
- Avalanche - Token usage, distribution, rewards
- Interfaces - Interfacing of controls
- LGE - LGE Claims
- Lodge - NFTs
- Loyalty - Flash loan discounts
- Patrol - Governance
- Pools - Yield Farming
- Registry - Deploy scripts, setup LGE board distrobution
- Slopes - Yield Farming
- Token - PWDR Token contract
- Upgrades - Update inheritance chain, bring all components into ecosystem
- Utils - LGE Claims, lodge staking, token usage
- Vaults - Update with Loyalty contract

### Main User Concern
*Explain where the risks of your users are mainly concerned. 
Including who has control (multi-sigs, DAOs, etc.) and what is capable from the entity capable of control/modification. 
This is where your users should be convinced that coverage is valuable for them and the protocol.*

- Platform exploitation and TVL drain
- Flash loan eploitation
- 50% of initial LGE is locked controlled by DAO, safe from exploit
- Remaining TVL of system is exposed to development or exploit risk and seeking coverage

### Possible Incident List
*Preferably list out possible incidents that can occur and that the team of PWDR would like coverage on.*
- Platform exploitation and TVL drain
- Flash loan exploitation

# Checklist
### Do you understand how Cover Protocol works?
**`Yes or No`**
Yes

If answer is **NO**, please go to our [documentation site](https://docs.coverprotocol.com) to get familiar with Cover Protocol before proceed. 

### [Optionl] What kind of collateral do you prefer?
**`yDai: 0x16de59092dae5ccf4a1e6439d611fd0653f0bd01`**

*Recommendation: a yield earning collateral will attract more liquidity for coverages of your protocol.*

### [Optionl] What kind of expiration date do you prefer?
**`30 days from initial release`**

*Recommendation: due to the fast nature of DeFi, we recommend monthly (default) expiration date.*

### Will you sponsor a bonus token for the CLAIM/NOCLAIM trading pools?
* **`Yes to be included at later time`**
* If **YES**,
  * Amount: **`1,000`**
  * Token Address: **`the bonus token address`**
  * Duration: **`6 months`**.

*Read about bonus token program [here](https://app.gitbook.com/@cover-protocol/s/docs/collaboration/bonus).*

### Will you become a Market Maker (MM) and/or Coverage Provider (CP)?
**`Market Maker and Coverage Provider`**

*Recommendation: using the majority of the fund to be a Market Maker to allow users to have access to liquidity. Then, using the rest of the fund to be a CP to decrease the cost of the coverage, aka CLAIM tokens.*

### How much in funds will be provided as coverage for the Protocol? 
* **`$20,000`** Collateral as MM
* **`$10,000`** Collateral as CP

### Will you be able to work with Cover Protocol to initiate the coverage for your protocol?
**`Yes `**

If **NO**, there will be a charge of **1 ETH** to cover deploy cost. Please send it to our dev multi-sig **0x15957f0CA310d35b2E73fB5070Ce44A5B0141AB1**.

If **YES**, follow [instructions here](https://docs.coverprotocol.com/collaboration/new).

### How can we contact you?
*Please list a person of contact and the communication channel (discord or telegram).*
**Discord** - edmundhillary#1156 or hmd#4131
