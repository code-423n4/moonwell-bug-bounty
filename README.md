# Moonwell Bug Bounty

- Max Critical Payout: $250,000 USDC/USDT
- High Severity Payout: $15,000 - $20,000 USDC/USDT
- Medium Severity Payout: $1,000 USDC/USDT

The payout for smart contract vulnerabilities is dependent on the amount of funds at risk due to the vulnerability, which will be determined by the maximum value of funds at risk in the contract(s) that are impacted on the date of submission of the report.

The following ratio will apply to the payouts for smart contract vulnerabilities, based on the maximum value at risk on the date of submission:

- Less than $5,000,000 - 10% of bounty for that category
- Between $5,000,000 and $10,000,000 - 25%
- Between $10,000,000 and $50,000,000 - 50%
- Between $50,000,000 and $250,000,000 - 75%
- Above $250,000,000 - 100%

## Project Overview

Moonwell is deployed on the Base, Optimism, Moonbeam, and Moonriver networks, all of which are Ethereum Virtual Machine (EVM) compatible. This compatibility ensures that a broad spectrum of wallets can support Moonwell.

Moonwell enables users to lend their assets in single-sided liquidity pools, also known as money markets, and start earning a variable interest rate. Lending your digital assets on Moonwell is also the first step one must take before being able to Borrow other assets on Moonwell. 

The protocol allows users to leverage or "collateralize" their digital assets to borrow other assets. By supplying assets to Moonwell, users can obtain an over-collateralized loan(s). 

The maximum borrowing limit is determined by the value of the supplied collateral and the parameters set by Moonwell Governance.

### Further Technical Resources & Links

- **Previous audits:** [Link](https://docs.moonwell.fi/moonwell/protocol-information/audits)
- **Documentation:** Our system documentation, subject to change. [Link](https://docs.moonwell.fi/moonwell)
- **Website:** https://moonwell.fi
- **Twitter:** [@MoonwellDefi](https://x.com/MoonwellDeFi)
- **Discord:** https://discord.gg/moonwellfii


## Scope


| Contract | 
| ----------- | 
| [Smart Contract - Unitroller/Comptroller](https://basescan.org/address/0xfbb21d0380bee3312b33c4353c8936a0f13ef26c ) | 
| [Smart Contract - Temporal Governor](https://basescan.org/address/0x8b621804a7637b781e2BbD58e256a591F2dF7d51 ) | 
| [Smart Contract - Multi-Reward Distributor](https://basescan.org/address/0xe9005b078701e2A0948D2EaC43010D35870Ad9d2 ) | 
| [Smart Contract - Moonwell DAI](https://basescan.org/address/0x73b06d8d18de422e269645eace15400de7462417) |  
| [Smart Contract - Moonwell USDC](https://basescan.org/token/0xedc817a28e8b93b03976fbd4a3ddbc9f7d176c22) |  
| [Smart Contract - Moonwell wstETH](https://basescan.org/token/0x627fe393bc6edda28e99ae648fd6ff362514304b) | 
| [Smart Contract - Moonwell rETH](https://basescan.org/token/0xcb1dacd30638ae38f2b94ea64f066045b7d45f44) |  
| [Smart Contract - Moonwell USDbC](https://basescan.org/address/0x703843C3379b52F9FF486c9f5892218d2a065cC8) | 
| [Smart Contract - Moonwell WETH](https://basescan.org/address/0x628ff693426583D9a7FB391E54366292F509D457) | 
| [Smart Contract - Moonwell cbETH](https://basescan.org/address/0x3bf93770f2d4a794c3d9EBEfBAeBAE2a8f09A5E5) | 
| [Smart Contract - WETH Router](https://basescan.org/address/0x31CCFB038771d9bF486Ef7c7f3A9F91bE72124C4) | 
| [Smart Contract - WETH Unwrapper](https://basescan.org/address/0x1382cff3cee10d283dcca55a30496187759e4caf) |  
| [Smart Contract - Chainlink Oracle](https://basescan.org/address/0xEC942bE8A8114bFD0396A5052c36027f2cA6a9d0) | 
| [Smart Contract - cbETH Composite Oracle](https://basescan.org/address/0xb0ba0c5d7da4ec400c1c3e5ef2485134f89918c5) |
| [Smart Contract - wstETH Composite Oracle](https://basescan.org/address/0xa5A5892bCfca4642c6bD789Ca75f27774309Dcb7) |  
| [Smart Contract - rETH Composite Oracle](https://basescan.org/address/0x106c7f4f7f0F1B1B5973dD7b89CF3ac46420945F) |
| [Smart Contract - Native WELL](https://basescan.org/address/0xA88594D404727625A9437C3f886C7643872296AE) | 
| [Smart Contract - Wormhole Bridge Adapter](https://basescan.org/address/0x734AbBCe07679C9A6B4Fe3bC16325e028fA6DbB7) |
| [Smart Contract - Vote Collection](https://basescan.org/address/0xe0278B32c627FF6fFbbe7de6A18Ade145603e949) | 
| [Smart Contract - Ecosystem Reserve](https://basescan.org/address/0x65A633E8E379F9358C389c75ff1D913a92ab95B8) | 
| [Smart Contract - Ecosystem Reserve Controller](https://basescan.org/address/0x938FD93CBc45eCC4Bb8f2d1A69F45e593EEed514) |
| [Smart Contract - stkWELL](https://basescan.org/address/0xe66e3a37c3274ac24fe8590f7d84a2427194dc17) | 
| [Smart Contract - Unitroller](https://moonriver.moonscan.io/address/0x0b7a0EAA884849c6Af7a129e899536dDDcA4905E) | 
| [Smart Contract - Comptroller](https://moonriver.moonscan.io/address/0x8529ea4DBDcA738aA928d682ea9c1382Bf2Ff098) |
| [Smart Contract - Maximillion](https://moonriver.moonscan.io/address/0x1650C0AD9483158f9e240fd58d0E173807A80CcC) |
| [Smart Contract - ChainlinkOracle](https://moonriver.moonscan.io/address/0x892bE716Dcf0A6199677F355f45ba8CC123BAF60) | 
| [Smart Contract - JumpRateModel](https://moonriver.moonscan.io/address/0xC862A3af64a8d3C146E6c505a18c2B6c6a6601bf) |
| [Smart Contract - Moonwell MOVR](https://moonriver.moonscan.io/address/0x6a1A771C7826596652daDC9145fEAaE62b1cd07f) | 
| [Smart Contract - Moonwell BTC](https://moonriver.moonscan.io/address/0x6E745367F4Ad2b3da7339aee65dC85d416614D90) | 
| [Smart Contract - Moonwell ETH](https://moonriver.moonscan.io/address/0x6503D905338e2ebB550c9eC39Ced525b612E77aE) | 
| [Smart Contract - Moonwell USDC](https://moonriver.moonscan.io/address/0xd0670AEe3698F66e2D4dAf071EB9c690d978BFA8) |
| [Smart Contract - Moonwell USDT](https://moonriver.moonscan.io/address/0x36918B66F9A3eC7a59d0007D8458DB17bDffBF21) | 
| [Smart Contract - Moonwell FRAX](https://moonriver.moonscan.io/address/0x93Ef8B7c6171BaB1C0A51092B2c9da8dc2ba0e9D) | 
| [Smart Contract - MFAM Token](https://moonriver.moonscan.io/token/0xbb8d88bcd9749636bc4d2be22aac4bb3b01a58f1) | 
| [Smart Contract - Moonwell xcKSM](https://moonriver.moonscan.io/address/0xa0d116513bd0b8f3f14e6ea41556c6ec34688e0f) |
| [Smart Contract - Unitroller](https://moonscan.io/address/0x8E00D5e02E65A19337Cdba98bbA9F84d4186a180) | 
| [Smart Contract - Comptroller](https://moonscan.io/address/0x08cdBe8cf5D0c231c615FF493583e7af297B43cD) | 
| [Smart Contract - Maximillion](https://moonscan.io/address/0xe5Ef9310cC7E3437bAD83466675f24FD62A380c3) |
| [Smart Contract - JumpRateModel](https://moonscan.io/address/0x1Ce7e4928943d6A4820375eBe737204dc1E73755) | 
| [Smart Contract - ChainlinkOracle](https://moonscan.io/address/0xED301cd3EB27217BDB05C4E9B820a8A3c8B665f9) | 
| [Smart Contract - MErc20Delegate](https://moonscan.io/address/0x948CCfff51F894DBA5C250aa2844d58E169f8aD9) | 
| [Smart Contract - mGLMR](https://moonscan.io/address/0x091608f4e4a15335145be0A279483C0f8E4c7955) | 
| [Smart Contract - mDOT](https://moonscan.io/address/0xD22Da948c0aB3A27f5570b604f3ADef5F68211C3) | 
| [Smart Contract - mETH.mad](https://moonscan.io/address/0xc3090f41Eb54A7f18587FD6651d4D3ab477b07a4) | 
| [Smart Contract - mWBTC.mad](https://moonscan.io/address/0x24A9d8f1f350d59cB0368D3d52A77dB29c833D1D) | 
| [Smart Contract - mUSDC.mad](https://moonscan.io/address/0x02e9081DfadD37A852F9a73C4d7d69e615E61334) | 
| [Smart Contract - mFRAX](https://moonscan.io/address/0x1C55649f73CDA2f72CEf3DD6C5CA3d49EFcF484C) | 
| [Smart Contract - mUSDC.wh](https://moonscan.io/token/0x744b1756e7651c6d57f5311767eafe5e931d615b) | 
| [Smart Contract - mETH.wh](https://moonscan.io/token/0xb6c94b3a378537300387b57ab1cc0d2083f9aeac) |
| [Smart Contract - mWBTC.wh](https://moonscan.io/token/0xaaa20c5a584a9fecdfedd71e46da7858b774a9ce) | 
| [Smart Contract - mxcUSDT](https://moonscan.io/token/0x42a96c0681b74838ec525adbd13c37f66388f289) | 
| [Smart Contract - ClaimsProxy](https://moonscan.io/address/0x933fCDf708481c57E9FD82f6BAA084f42e98B60e) | 
| [Smart Contract - GovToken](https://moonscan.io/address/0x511aB53F793683763E5a8829738301368a2411E3) | 
| [Smart Contract - EcosystemReserveController](https://moonscan.io/address/0xCa889f40aae37FFf165BccF69aeF1E82b5C511B9) |
| [Smart Contract - EcosystemReserve](https://moonscan.io/address/0x7793E08Eb4525309C46C9BA394cE33361A167ba4) |
| [Smart Contract - StakedGovToken](https://moonscan.io/address/0x8568A675384d761f36eC269D695d6Ce4423cfaB1) | 
| [Smart Contract - Governor](https://moonbeam.moonscan.io/address/0xfc4DFB17101A12C5CEc5eeDd8E92B5b16557666d) | 
| [Smart Contract - Timelock](https://moonbeam.moonscan.io/address/0x3a9249d70dCb4A4E9ef4f3AF99a3A130452ec19B) | 
| [Smart Contract - Multichain Governor](https://moonbeam.moonscan.io/address/0x9A8464C4C11CeA17e191653Deb7CdC1bE30F1Af4)|
| [Smart Contract - Native WELL Router](https://moonbeam.moonscan.io/address/0xfb26a4947a38cb53e2d083c6490060ccce7438c5) |
| [Smart Contract - Native WELL Lockbox](https://moonscan.io/address/0x0d45033775b290d69462944289b7a402a651b460) |
| [Smart Contract - Wormhole Bridge Adapter](https://moonscan.io/address/0x734AbBCe07679C9A6B4Fe3bC16325e028fA6DbB7) |
| [Smart Contract - Wormhole Unwrapper Adapter](https://moonscan.io/address/0x85b6cb73b076309616dba529fa2b20e2a0a9eee9) |
| [Smart Contract - Claims Proxy](https://moonriver.moonscan.io/address/0x8568A675384d761f36eC269D695d6Ce4423cfaB1) |
| [Smart Contract - StakedGovToken](https://moonriver.moonscan.io/address/0xCd76e63f3AbFA864c53b4B98F57c1aA6539FDa3a) |
| [Web/App](http://moonwell.fi) |
| [Smart Contract - Governor](https://moonriver.moonscan.io/address/0x2BE2e230e89c59c8E20E633C524AD2De246e7370) | 
| [Smart Contract - Timelock](https://moonriver.moonscan.io/address/0x04e6322D196E0E4cCBb2610dd8B8f2871E160bd7) |


### Publicly Known Issues

<ins>The following are known issues and therefore are out of scope:</ins>

- Borrowing rewards for markets where a reward speed is not set do not accrue without a user calling claim (or someone calling claimBehalf).
- When setting reward speed = 0 and turning it back on for a market, rewards will accrue as if the new rate was always on.
- Assets which are supplied which a user hasn’t called ‘enterMarkets’ for can still be seized. This is working as designed.
- New markets must be added with no collateral factor, and some small amount of the collateral token supply must be burned in order to avoid market manipulation. This is a known issue.
- **Wormhole dependency**: If wormhole goes offline, or pauses their relayer or wormhole core contracts, the Multichain Governor and Vote Collector will not be able to function. This is because the Multichain Governor passes messages to the Wormhole contract, and the Vote Collector receives messages from the Wormhole Relayer. If Wormhole is offline, on either chain, the system is considered broken and will not function.
-  If users have proposals in flight, and the max user live proposals variable is updated to be less than its current value, the system invariant `live proposals <= maxUserLiveProposals` can be temporarily violated.
- Quorum can be updated to zero, and if it is, then a proposal with a single for
vote can pass.
- Setting too high of a quorum also means that a proposal is unlikely to ever be able to pass. This is because the system will not be able to reach quorum, and all proposals will go to the `Defeated` state.
- Gas limit can be updated through a governance proposal, and if an external chain has their opcodes repriced higher, and the governance contract does not update its gas limit, then the system can be broken. This is because the system will not be able to process any transactions on the external chain, and the system will be unable to process any governance proposals. To mitigate this, the governor would use the break glass guardian to recover system ownership. Alternatively, a governance proposal could occur on Moonbeam to update the gas limit. However, users on Base would not be able to participate until this vote passed and the proposal was bridged to Base.

- Because this governance system straddles two chains, it is important that the timestamps on both chains are within one minute of each other to prevent issues around double voting. If an external chain has timestamps more than one minute behind Moonbeam, then a user could propose a change on Moonbeam, and then bridge their tokens to the external chain. This would mean once voting opened up, it would look like this user has double the voting power than they should have. This is because the system would register their votes on both Moonbeam and the external chain as valid.
- If the Pause Guardian is malicious, they could wait for a governance proposal to grant another guardian the ability to pause the contract, then pause the contract, clearing this proposal from the active set of proposals. Then the community would need to wait 30 days before they could create, vote on and pass another proposal again.
- If the vote collection contracts on other chains are malicious, they could prevent the Multichain Governor from executing proposals, or pass proposals that are failing by registering incorrect vote counts.
- if Wormhole is paused or offline, the Multichain Governor will still be able to execute and pass proposals, however, users on other chains will not be able to submit or have their votes collected.
- If Wormhole becomes malicious, it could register incorrect vote counts or prevent the Multichain Governor from executing proposals.

- Approved calldata is correctly set for the Break Glass Guardian. Incorrect calldata could allow the Break Glass Guardian to call any function on any contract. Side effects of incorrect configuration include but are not limited to:
- Complete loss of governance abilities on both Base and or Moonbeam deployments
- Setting of incorrect oracle data
- Arbitrary changes to governance parameters
- The block timestamp does not differ by more than 45 seconds between Moonbeam and the external chain:
- At a larger time difference than 45 seconds, the vote collection contract is at risk of allowing users to register double votes by first voting on Moonbeam, and then bridging to and voting on an external chain.
- The Wormhole bridge is live and working properly.
- If Wormhole is paused or offline, the Vote Collection contract will still be able to collect votes, however, votes will not be able to be sent to the Multichain Governor.
- If Wormhole becomes malicious, it could prevent the Vote Collection contract from collecting votes by blocking a new valid proposal from being registered.
- No bounties will be paid for issues that arise from a governor turning malicious. Instead, the researcher must demonstrate how the code is vulnerable without using known issues and provide a working PoC of the exploit to demonstrate this vulnerability.

### Out of scope

All issues reported in past audits are out of scope: https://docs.moonwell.fi/moonwell/protocol-information/audits 


## Miscellaneous

The Lunar Technology Foundation requires KYC to be completed by all researchers submitting a report before a bounty can be paid. The information needed is an ID scan along with a selfie to verify identity.

Current and past contractors or employees of Lunar Labs, Solidity Labs and Moonwell Foundation are not eligible for any rewards from this bug bounty program.
