# Pool FAQ & Troubleshooting

## Troubleshooting

### **I can't find the Pool I was staking in!**

You should be able to find the Pool under the “Finished” tab on the Pools page.

By selecting “Staked Only”, it will make it easier to find your assets.

### **Why did my earned tokens go to zero after staking/unstaking?**

Don’t worry! They’re in your wallet already.

Whenever you stake or unstake from a Pool or farm, your earned tokens get harvested and sent to your wallet at the same time.

## **General Questions**

### How is APR for Pools calculated?

> Syrup Pool APR = Annualized rewards (USD) / User funds staked in Syrup Pool (USD) \* 100

As a basic example, let's take a 60-day pool with 300,000 USD worth of rewards, and 3,000,000 USD worth of DESIRE staked in it.

The APR fluctuates as more DESIRE is staked by users, and as the price of DESIRE, and the reward token, vary.

|                                                         | **Calculation**                  | Amount            |
| ------------------------------------------------------- | -------------------------------- | ----------------- |
| Total rewards to distribute (USD value)                 |                                  | 300,000 USD       |
| Distribution period                                     |                                  | 60 days           |
| Daily distribution                                      | 300,000 / 60 =                   | 5,000 USD daily   |
| **Annualised rewards (USD value)**                      | 5,000 \* 365 =                   | **1,825,000 USD** |
| **Value of DESIRE staked by users in pool (USD value)** |                                  | **3,000,000 USD** |
| **APR**                                                 | (1,825,000 / 3,000,000) \* 100 = | **60.833% APR**   |

### **What does the “End” number on my Pool refer to?**

This shows the amount of blocks left until the rewards for that pool stop being distributed. Once the pool has reached that block, you should unstake your tokens, because you won’t be receiving any rewards after that.

### **Where do the rewards from Pools come from?**

There are three main types of Pools.

1. Stake DESIRE, earn DESIRE
2. Stake DESIRE, earn other tokens.
3. Stake other tokens, earn DESIRE

The rewards for the "Stake DESIRE, earn DESIRE" Pools come from the DESIRE emissions. Each block, a number of DESIRE tokens are allocated as rewards for these pools.

The rewards for the "Stake DESIRE, earn other tokens" type are provided by the project teams who sponsor a Pool.

For the "Stake other tokens, earn DESIRE" type, the TasteDEX treasury buys back DESIRE from the market to distribute as rewards. These pools are funded by TasteDEX, not by the projects themselves.
