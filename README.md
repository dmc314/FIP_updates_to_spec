# FIP_updates_to_spec
Organizing Updates to the Filecoin Spec from FIPs

distribution of humanity’s information. To help the network grow and evolve, it is critical for the community to collectively be engaged in proposing, discussing, and implementing changes that improve the network and its operations.

This improvement protocol helps achieve that objective for all members of the Filecoin community (developers, miners, clients, token holders, ecosystem partners, and more).


|FIP #   | Title  | Type  | Author  | Status  |
|---|---|---|---|---|
|[0001](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0001.md)   | FIP Purpose and Guidelines  | FIP  | @Whyrusleeping  | Active  |
|[0002](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0002.md)   | Free Faults on Newly Faulted Sectors of a Missed WindowPoSt  | FIP | @anorth, @davidad, @miyazono, @irenegia, @lucaniz, @nicola, @zixuanzh   |Final   |
|[0003](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0003.md)   | Filecoin Plus Principles  | FIP  | @feerst, @jbenet, @jnthnvctr, @tim-murmuration, @mzargham, @zixuanzh  |Active   |
|[0004](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0004.md)   | Liquidity Improvement for Storage Miners   | FIP  | @davidad, @jbenet, @zenground0, @zixuanzh, @danlessa   | Final  |
|[0005](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0005.md)   | Remove ineffective reward vesting    | FIP  | @anorth, @Zenground   |Final   |
|[0006](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0006.md)   | No repay debt requirement for DeclareFaultsRecovered  | FIP  |  @nicola, @irenegia  | Deferred  |
|[0007](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0007.md)   | h/amt-v3  | FIP  | @rvagg, @Stebalien, @anorth, @Zenground0   |Final   |
|[0008](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0008.md)   | Add miner batched sector pre-commit method  | FIP  |@anorth, @ZenGround0, @nicola  |Final   |
|[0009](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0009.md)   | Exempt Window PoSts from BaseFee burn  | FIP  |@Stebalien, @momack2, @magik6k, @zixuanzh  |Final   |
|[0010](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0010.md)   | Off-Chain Window PoSt Verification  | FIP  |@Stebalien, @anorth  |Final  |
|[0011](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0011.md)   | Remove reward auction from reporting consensus faults  | FIP  |@Kubuxu |Final   |
|[0012](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0012.md)   | DataCap Top up for FIL+ Client Addresses  | FIP  |@dshoy, @jnthnvctr, @zx |Final  |
|[0013](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0013.md)   | Add ProveCommitSectorAggregated method to reduce on-chain congestion  | FIP  | @ninitrava @nicola |Final   |
|[0014](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0014.md)   | Allow V1 proof sectors to be extended up to a maximum of 540 days | FIP  | @deltazxm, @neogeweb3 |Final   |
|[0015](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0015.md)   | Revert FIP-0009(Exempt Window PoSts from BaseFee burn) | FIP  | @jennijuju, @arajasek |Final   |
|[0016](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0016.md)   | Pack arbitrary data in CC sectors | FIP  | donghengzhao (@1475) |Deferred  |
|[0017](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0017.md)   | Three-messages lightweight sector updates | FIP  |@nicole, @lucaniz, @irenegia |Deferred  |
|[0018](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0018.md)   | New miner terminology proposal | FIP  |@Stefaan-V |Final  |
|[0019](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0019.md)   | Snap Deals | FIP  |@Kubuxu, @lucaniz, @nicola, @rosariogennaro, @irenegia |Final  |
|[0020](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0020.md)   | Add return value to WithdrawBalance | FIP  |@Stefaan-V |Final  |
|[0021](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0021.md)   | Correct quality calculation on expiration | FIP  |@Steven004, @Zenground0 |Final  |
|[0022](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0022.md)   | Bad deals don't fail PublishStorageDeals | FIP  |@Zenground0 |Final  |
|[0023](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0023.md)   | Break ties between tipsets of equal weights | FIP  |@sa8, @arajasek |Final  |
|[0024](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0024.md)   | BatchBalancer & BatchDiscount Post -Hyperdrive adjustment | FIP  |@zx, @jbenet, @zenground0, @momack2 |Final  |
|[0025](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0025.md)   | Handle expired deals in ProveCommit | FIP  |@ZenGround0 |Deferred  |
|[0026](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0026.md)   | Extend sector fault cutoff period from 2 weeks to 6 weeks | FIP  |@IPFSUnion |Final  |
|[0027](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0027.md)   | Change type of DealProposal Label field from a (Golang) String to a Union | FIP  |@laudiacay, @Stebalien, @arajasek |Accepted  |
|[0028](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0028.md)   | Remove DataCap and verified client status from client address | FIP  |@jennijuju, @dkkapur |Final  |
|[0029](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0029.md)   | Beneficiary address for storage providers | FIP  |@steven004 |Accepted  |
|[0030](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0030.md)   | Introducing the Filecoin Virtual Machine (FVM) | FIP  |@raulk, @stebalien |Final  |
|[0031](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0031.md)   | Atomic switch to non-programmable FVM | FIP  |@raulk, @stebalien |Final  |
|[0032](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0032.md)   | Gas model adjustment for non-programmable FVM | FIP  |@raulk, @stebalien |Final  |
|[0033](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0033.md)   | Explicit premium for FIL+ verified deals | FIP  |@anorth |Deferred  |
|[0034](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0034.md)   | Fix pre-commit deposit independent of sector content | FIP  |@anorth, @Kubuxu |Accepted |
|[0035](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0035.md)   | Support actors as built-in storage market clients | FIP  |@anorth |Withdrawn  |
|[0036](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0036.md)   | Introducing a Sector Duration Multiple for Longer Term Sector Commitment | FIP  |@AxCortesCubero, @jbenet, @misilva73, @momack2, @tmellan, @vkalghatgi, @zixuanzh |Rejected  |
|[0037](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0037.md)   | Gas model adjustment for user programmability | FIP  |@raulk, @stebalien |Draft  |
|[0038](https://github.com/filecoin-project/FIPs/blob/master/FRCs/frc-0038.md)   | Indexer Protocol for Filecoin Content Discovery | FRC  |@willscott, @gammazero, @honghaoq |Draft  |
|[0039](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0039.md)   | Filecoin Message Replay Protection | FIP  |@q9f |Draft  |
|[0040](https://github.com/filecoin-project/FIPs/blob/master/FRCs/frc-0040.md)   | Boost - Filecoin Storage Deals Market Protocol | FRC  |@dirkmc, @nonsense, @jacobheun, @brendalee |Draft  |
|[0041](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0041.md)   | Forward Compatibility for PreCommit and ReplicaUpdate | FIP  |@Kubuxu |Accepted  |
|[0042](https://github.com/filecoin-project/FIPs/blob/master/FRCs/frc-0042.md)   | Calling Convention for Hashed Method Name | FRC  |@Kubuxu, @anorth |Draft  |
|[0044](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0044.md)   | Standard Authentication Method for Actors | FIP  |@arajasek, @anorth |Accepted  |
|[0045](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0045.md)   | De-couple verified registry from markets | FIP  |@anorth, @zenground0 |Accepted  |
|[0046](https://github.com/filecoin-project/FIPs/blob/master/FRCs/frc-0046.md)   | Fungible token standard | FRC  |@anorth, @jsuresh, @alexytsu |Draft  |
|[0047](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0047.md)   | Proof Expiration & PoRep Security Policy | FIP  |@Kubuxu, @irenegia, @anorth |Accepted  |
|[0048](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0048.md)   | f4 Address Class | FIP  |@stebalien, @mriise, @raulk | Draft  |
|[0049](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0049.md)   | Actor Events | FIP  |@stebalien, @raulk | Draft  |
|[0050](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0050.md)   | API Between User-Programmed Actors and Built-In Actors | FIP  |@anorth, @arajasek | Draft  |
|[0052](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0052.md)   | Increase max sector commitment to 3.5 years | FIP  |@anorth | Draft  |
|[0053](https://github.com/filecoin-project/FIPs/blob/master/FRCs/frc-0053.md)   | Non-Fungible Token Standard | FRC  |@alexytsu, @abright, @anorth | Draft  |
