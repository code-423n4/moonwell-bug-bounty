# Moonwell Bug Bounty Details

- [Read our guidelines for more details](https://docs.code4rena.com/bounties)
- Submit findings [using the C4 form](https://code4rena.com/bounties/moonwell/submit)


**Smart Contracts:**

| Risk Score |  Payout |
|------------|---------|
| Critical | Up to USDC &#36;250,000 |
| High| USDC &#36;15,000 - &#36;20,000 |
| Medium | USDC &#36;1,000 - &#36;5,000 Gratuity range|


**Quick Links:**
- [Judging for C4 Bug Bounties](https://docs.code4rena.com/awarding/judging-criteria/bounty-judging)
- [Criteria for C4 Bug Bounties](https://docs.code4rena.com/awarding/judging-criteria/bounty-criteria)

## Background on Moonwell

Moonwell is an open lending, borrowing, and decentralized finance protocol built on Base, Optimism, Moonbeam and Moonriver. Moonwell's multichain design brings the world onchain with simple, yet powerful financial tools. This bug bounty program is focused on their smart contracts, website and app with a focus on preventing:
- Loss of protocol or user funds
- Smart contract vulnerabilities
- Denial of service issues
- Infrastructure vulnerabilities
- Social media administrative control breaches

### Further Technical Resources & Links

- **Moonwell Docs**: Our system documentation, subject to change. [Link](https://docs.moonwell.fi/moonwell)
- **Moonwell Previous Audits:** Our previous audits - [Link](https://docs.moonwell.fi/moonwell/protocol-information/audits )
- **Moonwell Website**: [Link](https://moonwell.fi)
- **Twitter:** [@MoonwellDefi](https://x.com/MoonwellDeFi)
- **Discord:** https://discord.gg/moonwellfii

# Scope & Severity Criteria

**Websites and Applications**
- Domain takeover for moonwell.fi 

The payout for smart contract vulnerabilities depends on the amount of funds at risk due to the vulnerability. This, will be determined by the maximum value of funds at risk in the impacted contract(s) at the time of report submission

The following ratio will apply to the smart contract vulnerabilities payouts:

- Less than &#36;5,000,000 - 10% of bounty for that category
- Between &#36;5,000,000 and &#36;10,000,000 - 25%
- Between &#36;10,000,000 and &#36;50,000,000 - 50%
- Between &#36;50,000,000 and &#36;250,000,000 - 75%
- Above &#36;250,000,000 - 100%

Only the following impacts are accepted within this bug bounty program. All other impacts are not considered as in-scope, even if they affect something in the assets in scope table.

## Smart Contracts in Scope

Rewards for critical smart contract vulnerabilities are further capped at 10% of economic damage, with the main consideration being the funds affected in addition to PR and brand considerations, at the discretion of the team. However, there is a minimum reward of USDC $100,000 for Critical bug reports. 

Payouts are handled by the Moonwell team directly and are denominated in USDC. Payouts will be made in USDC or USDT at the team's discretion. 

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
| [Smart Contract - Moonwell wrsETH](https://basescan.org/address/0xfC41B49d064Ac646015b459C522820DB9472F4B5) |
| [Smart Contract - Well](https://optimistic.etherscan.io/address/0xA88594D404727625A9437C3f886C7643872296AE) |
| [Smart Contract - Unitroller/Comptroller](https://optimistic.etherscan.io/address/0x8dFBb21dbD61af533092d54B293660CF77A30Ce2)|
| [Smart Contract - MRD Proxy Admin](https://optimistic.etherscan.io/address/0x8568A675384d761f36eC269D695d6Ce4423cfaB1) |
| [Smart Contract - Temporal Governor](https://optimistic.etherscan.io/address/0x17C9ba3fDa7EC71CcfD75f978Ef31E21927aFF3d)| 
| [Smart Contract - Multi-Reward Distributor](https://optimistic.etherscan.io/address/0xF9524bfa18C19C3E605FbfE8DFd05C6e967574Aa) |
| [Smart Contract - Moonwell weETH](https://optimistic.etherscan.io/address/0xb8051464C8c92209C92F3a4CD9C73746C4c3CFb3)|
| [Smart Contract - Moonwell USDC](https://optimistic.etherscan.io/address/0x8E08617b0d66359D73Aa11E11017834C29155525) |
| [Smart Contract - Moonwell USDT](https://optimistic.etherscan.io/address/0xa3A53899EE8f9f6E963437C5B3f805FEc538BF84) |
| [Smart Contract - Moonwell DAI](https://optimistic.etherscan.io/address/0x3FE782C2Fe7668C2F1Eb313ACf3022a31feaD6B2) |
| [Smart Contract - Moonwell wBTC](https://optimistic.etherscan.io/address/0x6e6CA598A06E609c913551B729a228B023f06fDB) |
| [Smart Contract - Moonwell wETH](https://optimistic.etherscan.io/address/0xb4104C02BBf4E9be85AAa41a62974E4e28D59A33) |
| [Smart Contract - Moonwell wstETH](https://optimistic.etherscan.io/address/0xbb3b1aB66eFB43B10923b87460c0106643B83f9d) |
| [Smart Contract - Moonwell cbETH](https://optimistic.etherscan.io/address/0x95C84F369bd0251ca903052600A3C96838D78bA1) |
| [Smart Contract - Moonwell cbETH](https://optimistic.etherscan.io/address/0x4c2E35E3eC4A0C82849637BC04A4609Dbe53d321) |
| [Smart Contract - Moonwell VELO](https://optimistic.etherscan.io/address/0x866b838b97Ee43F2c818B3cb5Cc77A0dc22003Fc) |
| [Smart Contract - Moonwell OP](https://optimistic.etherscan.io/address/0x9fc345a20541Bf8773988515c5950eD69aF01847) |
| [Smart Contract - Moonwell wrsETH](https://basescan.org/address/0xfC41B49d064Ac646015b459C522820DB9472F4B5 ) |
| [Smart Contract - Native WELL](https://optimistic.etherscan.io/address/0xA88594D404727625A9437C3f886C7643872296AE) |
| [Smart Contract - Wormhole Bridge Adapter](https://optimistic.etherscan.io/address/0x734AbBCe07679C9A6B4Fe3bC16325e028fA6DbB7) |
| [Smart Contract - Vote Collection](https://optimistic.etherscan.io/address/0x3C968481BE3ba1a99fed5f73dB2Ff51151037738) |
| [Smart Contract - Ecosystem Reserve](https://optimistic.etherscan.io/address/0x966450Ee0757846963F17f7978a8A906e078EF4b) |
| [Smart Contract - Ecosystem Reserve Controller](https://optimistic.etherscan.io/address/0x1D776f9dc5fb96a2B60862973d90418d684dEE1e) |
| [Smart Contract - stkWELL](https://optimistic.etherscan.io/address/0xfB26A4947A38cb53e2D083c6490060CCCE7438c5) |
| [Smart Contract - USDC Strategy Factory](https://basescan.org/address/0x5967ea71cC65d610dc6999d7dF62bfa512e62D07) | 
| [Smart Contract - Mamo Strategy Registry](https://basescan.org/address/0x46a5624C2ba92c08aBA4B206297052EDf14baa92) |
| [Smart Contract - ERC20 Moonwell Market and Morpho Vault Strategy](https://basescan.org/address/0x5fAB373f43079CE488C2b8579751791982C03A35) |
| [Smart Contract - Slippage Price Checker](https://basescan.org/address/0x5A8F10be44E25Bb21492C5f46DA94cDb1f0b2fF6) |
| [Smart Contract - cbBTC Strategy Factory](https://basescan.org/address/0xE23c8E37F256Ba5783351CBb7B6673FE68248712) |

Source code for the above-listed contracts is available in [Moonwell's public Github repositories](https://github.com/moonwell-fi).

## Out-of-Scope

### Known Issues

Bug reports covering previously-discovered bugs (listed below) are not eligible for a reward within this program. This includes known issues that the project is aware of but has consciously decided not to “fix”, necessary code changes, or any implemented operational mitigating procedures that can lessen potential risk. Every issue opened in the repo, closed PRs, previous contests and audits are out of scope.

The following are known issues and therefore are out of scope:

- [Bug in Base Safety Module allows some users to claim the full reward budget from MIP-X28](https://forum.moonwell.fi/t/pre-bug-remediation-rewards-for-the-base-safety-module/1859/1)
- Borrowing rewards for markets where a reward speed is not set do not accrue without a user calling claim (or someone calling claimBehalf).
- When setting reward speed = 0 and turning it back on for a market, rewards will accrue as if the new rate was always on.
- Assets which are supplied which a user hasn’t called ‘enterMarkets’ for can still be seized. This is working as designed.
- New markets must be added with no collateral factor, and some small amount of the collateral token supply must be burned in order to avoid market manipulation. This is a known issue.
- Wormhole dependency: If wormhole goes offline, or pauses their relayer or wormhole core contracts, the Multichain Governor and Vote Collector will not be able to function. This is because the Multichain Governor passes messages to the Wormhole contract, and the Vote Collector receives messages from the Wormhole Relayer. If Wormhole is offline, on either chain, the system is considered broken and will not function.
-  If users have proposals in flight, and the max user live proposals variable is updated to be less than its current value, the system invariant `live proposals <= maxUserLiveProposals` can be temporarily violated.
- Quorum can be updated to zero, and if it is, then a proposal with a single for
vote can pass.
- Setting too high of a quorum also means that a proposal is unlikely to ever be able to pass. This is because the system will not be able to reach quorum, and all proposals will go to the `Defeated` state.
- Gas limit can be updated through a governance proposal, and if an external chain has their opcodes repriced higher, and the governance contract does not update its gas limit, then the system can be broken. This is because the system will not be able to process any transactions on the external chain, and the system will be unable to process any governance proposals. To mitigate this, the governor would use the break glass guardian to recover system ownership. Alternatively, a governance proposal could occur on Moonbeam to update the gas limit. However, users on Base would not be able to participate until this vote passed and the proposal was bridged to Base.
- Because the governance system straddles three chains, it is important that the timestamps on all chains are within one minute of each other to prevent issues around double voting. If an external chain has timestamps more than one minute behind Moonbeam, then a user could propose a change on Moonbeam, and then bridge their tokens to the external chain. This would mean once voting opened up, it would look like this user has double the voting power than they should have. This is because the system would register their votes on both Moonbeam and the external chain as valid.
- if the Pause Guardian is malicious, they could wait for a governance proposal to grant another guardian the ability to pause the contract, then pause the contract, clearing this proposal from the active set of proposals. Then the community would need to wait 30 days before they could create, vote on and pass another proposal again.
- if the vote collection contracts on other chains are malicious, they could prevent the Multichain Governor from executing proposals, or pass proposals that are failing by registering incorrect vote counts.
- if Wormhole is paused or offline, the Multichain Governor will still be able to execute and pass proposals, however, users on other chains will not be able to submit or have their votes collected.
- if Wormhole becomes malicious, it could register incorrect vote counts or prevent the Multichain Governor from executing proposals.
- Approved calldata is correctly set for the Break Glass Guardian. Incorrect calldata could allow the Break Glass Guardian to call any function on any contract. Side effects of incorrect configuration include but are not limited to:
- complete loss of governance abilities on both Base, Optimism, and or Moonbeam deployments
- setting of incorrect oracle data
- arbitrary changes to governance parameters
- The block timestamp does not differ by more than 45 seconds between Moonbeam and the external chain:
- at a larger time difference than 45 seconds, the vote collection contract is at risk of allowing users to register double votes by first voting on Moonbeam, and then bridging to and voting on an external chain.
- The Wormhole bridge is live and working properly.
- if Wormhole becomes malicious, it could prevent the Vote Collection contract from collecting votes by blocking a new valid proposal from being registered.
- if Wormhole is paused or offline, the Vote Collection contract will still be able to collect votes, however, votes will not be able to be sent to the Multichain Governor.
- No bounties will be paid for issues that arise from a governor turning malicious. Instead, the researcher must demonstrate how the code is vulnerable without using known issues and provide a working PoC of the exploit to demonstrate this vulnerability.
- Temporal Governor on Base cannot receive raw ether as it has no payable fallback function. This means reserves cannot be sent to it from the ETH market. This is a known issue.

### Previous Audits

All issues reported in past audits are out of scope and are not eligible for a reward https://docs.moonwell.fi/moonwell/protocol-information/audits.

No bounties will be paid for issues that arise from a governor turning malicious. Instead, the researcher must demonstrate how the code is vulnerable without using known issues and provide a working PoC of the exploit to demonstrate this vulnerability. Reports for critical and high severity issues will require the researcher to write a PoC to receive a payout on all critical or high severity issues.
Known issues are out of scope, such as double voting assuming block timestamps between chains drift far enough apart

### Specific Types of Issues

The following vulnerabilities are excluded from the rewards for this bug bounty program:

- Attacks that the reporter has already exploited themselves, leading to damage
- Attacks requiring access to leaked keys/credentials
- Attacks requiring access to privileged addresses (governance, strategist)
- 3rd party services (AWS, Datadog, etc)


The following activities are prohibited by this bug bounty program:

- Any testing with mainnet or public testnet contracts; all testing should be done on private testnets
- Any testing with pricing oracles or third party smart contracts
- Attempting phishing or other social engineering attacks against our employees and/or customers
- Any testing with third party systems and applications (e.g. browser extensions) as well as websites (e.g. SSO providers, advertising networks)
- Any denial of service attacks
- Automated testing of services that generates significant amounts of traffic
- Public disclosure of an unpatched vulnerability in an embargoed bounty


# Additional Context

### Trusted Roles

The only trusted roles on Moonwell smart contracts are for the governor or DAO (admin/owner), pause guardian roles for the Moonwell security council, and a Governance guardian role that can pause governance in the event of a bridge compromise.

### Miscellaneous
The Moonwell Foundation requires all researchers submitting a report to complete KYC and a sanctions screening before a bounty can be paid.

Current and past contractors or employees of Lunar Labs, Solidity Labs, and Moonwell Foundation are not eligible for any rewards from this bug bounty program.
