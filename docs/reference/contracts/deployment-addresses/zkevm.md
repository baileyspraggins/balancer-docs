

# Zkevm Deployment Addresses

::: info More Details
For more information on specific deployments as well as changelogs for different contract versions, please see the [deployment tasks](https://github.com/balancer/balancer-deployments/tree/master/tasks).
:::

## Pool Factories

| Contract                         | Address                                                                                                                              | Deployment                                                                                                                                  |
|:---------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------|
| AaveLinearPoolFactory (v5)       | [0x4b7b369989e613ff2C65768B7Cf930cC927F901E](https://zkevm.polygonscan.com//address/0x4b7b369989e613ff2C65768B7Cf930cC927F901E#code) | [20230410-aave-linear-pool-v5](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230410-aave-linear-pool-v5)             |
| ComposableStablePoolFactory (v5) | [0x956CCab09898C0AF2aCa5e6C229c3aD4E93d9288](https://zkevm.polygonscan.com//address/0x956CCab09898C0AF2aCa5e6C229c3aD4E93d9288#code) | [20230711-composable-stable-pool-v5](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230711-composable-stable-pool-v5) |
| ERC4626LinearPoolFactory (v4)    | [0x6B1Da720Be2D11d95177ccFc40A917c2688f396c](https://zkevm.polygonscan.com//address/0x6B1Da720Be2D11d95177ccFc40A917c2688f396c#code) | [20230409-erc4626-linear-pool-v4](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230409-erc4626-linear-pool-v4)       |
| GearboxLinearPoolFactory (v2)    | [0x687b8C9b41E01Be8B591725fac5d5f52D0564d79](https://zkevm.polygonscan.com//address/0x687b8C9b41E01Be8B591725fac5d5f52D0564d79#code) | [20230409-gearbox-linear-pool-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230409-gearbox-linear-pool-v2)       |
| ManagedPoolFactory (v2)          | [0xaf779e58dafb4307b998C7b3C9D3f788DFc80632](https://zkevm.polygonscan.com//address/0xaf779e58dafb4307b998C7b3C9D3f788DFc80632#code) | [20230411-managed-pool-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230411-managed-pool-v2)                     |
| WeightedPoolFactory (v4)         | [0x03F3Fb107e74F2EAC9358862E91ad3c692712054](https://zkevm.polygonscan.com//address/0x03F3Fb107e74F2EAC9358862E91ad3c692712054#code) | [20230320-weighted-pool-v4](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230320-weighted-pool-v4)                   |
| YearnLinearPoolFactory (v2)      | [0x44d33798dddCdAbc93Fe6a40C80588033Dc502d3](https://zkevm.polygonscan.com//address/0x44d33798dddCdAbc93Fe6a40C80588033Dc502d3#code) | [20230409-yearn-linear-pool-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230409-yearn-linear-pool-v2)           |

## Core

| Contract                       | Address                                                                                                                              | Deployment                                                                                                                                                  |
|:-------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------|
| BalancerQueries                | [0x809B79b53F18E9bc08A961ED4678B901aC93213a](https://zkevm.polygonscan.com//address/0x809B79b53F18E9bc08A961ED4678B901aC93213a#code) | [20220721-balancer-queries](https://github.com/balancer/balancer-deployments/blob/master/tasks/20220721-balancer-queries)                                   |
| BalancerRelayer                | [0x4678731DC41142A902a114aC5B2F77b63f4a259D](https://zkevm.polygonscan.com//address/0x4678731DC41142A902a114aC5B2F77b63f4a259D#code) | [20230314-batch-relayer-v5](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230314-batch-relayer-v5)                                   |
| BatchRelayerLibrary            | [0x54f8F9d28e26Fa5864cfA80f50A5Df95fD85f46a](https://zkevm.polygonscan.com//address/0x54f8F9d28e26Fa5864cfA80f50A5Df95fD85f46a#code) | [20230314-batch-relayer-v5](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230314-batch-relayer-v5)                                   |
| ProtocolFeePercentagesProvider | [0x1802953277FD955f9a254B80Aa0582f193cF1d77](https://zkevm.polygonscan.com//address/0x1802953277FD955f9a254B80Aa0582f193cF1d77#code) | [20220725-protocol-fee-percentages-provider](https://github.com/balancer/balancer-deployments/blob/master/tasks/20220725-protocol-fee-percentages-provider) |
| Vault                          | [0xBA12222222228d8Ba445958a75a0704d566BF2C8](https://zkevm.polygonscan.com//address/0xBA12222222228d8Ba445958a75a0704d566BF2C8#code) | [20210418-vault](https://github.com/balancer/balancer-deployments/blob/master/tasks/20210418-vault)                                                         |

## Authorization

| Contract                        | Address                                                                                                                              | Deployment                                                                                                                                          |
|:--------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| Authorizer                      | [0xA331D84eC860Bf466b4CdCcFb4aC09a1B43F3aE6](https://zkevm.polygonscan.com//address/0xA331D84eC860Bf466b4CdCcFb4aC09a1B43F3aE6#code) | [20210418-authorizer](https://github.com/balancer/balancer-deployments/blob/master/tasks/20210418-authorizer)                                       |
| AuthorizerAdaptor               | [0xdcdbf71A870cc60C6F9B621E28a7D3Ffd6Dd4965](https://zkevm.polygonscan.com//address/0xdcdbf71A870cc60C6F9B621E28a7D3Ffd6Dd4965#code) | [20220325-authorizer-adaptor](https://github.com/balancer/balancer-deployments/blob/master/tasks/20220325-authorizer-adaptor)                       |
| AuthorizerAdaptorEntrypoint     | [0xb9aD3466cdd42015cc05d4804DC68D562b6a2065](https://zkevm.polygonscan.com//address/0xb9aD3466cdd42015cc05d4804DC68D562b6a2065#code) | [20221124-authorizer-adaptor-entrypoint](https://github.com/balancer/balancer-deployments/blob/master/tasks/20221124-authorizer-adaptor-entrypoint) |
| AuthorizerWithAdaptorValidation | [0x8df317a729fcaA260306d7de28888932cb579b88](https://zkevm.polygonscan.com//address/0x8df317a729fcaA260306d7de28888932cb579b88#code) | [20230414-authorizer-wrapper](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230414-authorizer-wrapper)                       |

## Gauges and Governance

| Contract                    | Address                                                                                                                              | Deployment                                                                                                                                        |
|:----------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------|
| ChildChainGauge             | [0x59562f93c447656F6E4799fC1FC7c3d977C3324F](https://zkevm.polygonscan.com//address/0x59562f93c447656F6E4799fC1FC7c3d977C3324F#code) | [20230316-child-chain-gauge-factory-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230316-child-chain-gauge-factory-v2) |
| ChildChainGaugeFactory      | [0x2498A2B0d6462d2260EAC50aE1C3e03F4829BA95](https://zkevm.polygonscan.com//address/0x2498A2B0d6462d2260EAC50aE1C3e03F4829BA95#code) | [20230316-child-chain-gauge-factory-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230316-child-chain-gauge-factory-v2) |
| L2LayerZeroBridgeForwarder  | [0xDEd7Fef7D8eCdcB74F22f0169e1A9EC696e6695d](https://zkevm.polygonscan.com//address/0xDEd7Fef7D8eCdcB74F22f0169e1A9EC696e6695d#code) | [20230404-l2-layer0-bridge-forwarder](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230404-l2-layer0-bridge-forwarder)     |
| ProtocolFeesCollector       | [0xce88686553686DA562CE7Cea497CE749DA109f9F](https://zkevm.polygonscan.com//address/0xce88686553686DA562CE7Cea497CE749DA109f9F#code) | [20210418-vault](https://github.com/balancer/balancer-deployments/blob/master/tasks/20210418-vault)                                               |
| ProtocolFeesWithdrawer      | [0x230a59F4d9ADc147480f03B0D3fFfeCd56c3289a](https://zkevm.polygonscan.com//address/0x230a59F4d9ADc147480f03B0D3fFfeCd56c3289a#code) | [20220517-protocol-fee-withdrawer](https://github.com/balancer/balancer-deployments/blob/master/tasks/20220517-protocol-fee-withdrawer)           |
| VeBoostV2                   | [0xE39B5e3B6D74016b2F6A9673D7d7493B6DF549d5](https://zkevm.polygonscan.com//address/0xE39B5e3B6D74016b2F6A9673D7d7493B6DF549d5#code) | [20230525-l2-veboost-v2](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230525-l2-veboost-v2)                               |
| VotingEscrowDelegationProxy | [0xc7E5ED1054A24Ef31D827E6F86caA58B3Bc168d7](https://zkevm.polygonscan.com//address/0xc7E5ED1054A24Ef31D827E6F86caA58B3Bc168d7#code) | [20230316-l2-ve-delegation-proxy](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230316-l2-ve-delegation-proxy)             |

## Ungrouped Active/Current Contracts
    
    
| Contract                                       | Address                                                                                                                              | Deployment                                                                                                                                        |
|:-----------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------|
| BAL                                            | [0x120eF59b80774F02211563834d8E3b72cb1649d6](https://zkevm.polygonscan.com//address/0x120eF59b80774F02211563834d8E3b72cb1649d6#code) | [00000000-tokens](https://github.com/balancer/balancer-deployments/blob/master/tasks/00000000-tokens)                                             |
| BalancerHelpers                                | [0x8E9aa87E45e92bad84D5F8DD1bff34Fb92637dE9](https://zkevm.polygonscan.com//address/0x8E9aa87E45e92bad84D5F8DD1bff34Fb92637dE9#code) | [20210418-vault](https://github.com/balancer/balancer-deployments/blob/master/tasks/20210418-vault)                                               |
| GaugeWorkingBalanceHelper                      | [0xEF454a7B3f965D3f6723E462405246f8Cd865425](https://zkevm.polygonscan.com//address/0xEF454a7B3f965D3f6723E462405246f8Cd865425#code) | [20230526-gauge-working-balance-helper](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230526-gauge-working-balance-helper) |
| L2BalancerPseudoMinter                         | [0x475D18169BE8a89357A9ee3Ab00ca386d20fA229](https://zkevm.polygonscan.com//address/0x475D18169BE8a89357A9ee3Ab00ca386d20fA229#code) | [20230316-l2-balancer-pseudo-minter](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230316-l2-balancer-pseudo-minter)       |
| MockLiquidityBootstrappingPool                 | [0x3c87FF3e9307dbEbfAe720E04C6439e49f79BF9B](https://zkevm.polygonscan.com//address/0x3c87FF3e9307dbEbfAe720E04C6439e49f79BF9B#code) | [20211202-no-protocol-fee-lbp](https://github.com/balancer/balancer-deployments/blob/master/tasks/20211202-no-protocol-fee-lbp)                   |
| NoProtocolFeeLiquidityBootstrappingPoolFactory | [0x3B1eb8EB7b43882b385aB30533D9A2BeF9052a98](https://zkevm.polygonscan.com//address/0x3B1eb8EB7b43882b385aB30533D9A2BeF9052a98#code) | [20211202-no-protocol-fee-lbp](https://github.com/balancer/balancer-deployments/blob/master/tasks/20211202-no-protocol-fee-lbp)                   |
| NullVotingEscrow                               | [0xD87F44Df0159DC78029AB9CA7D7e57E7249F5ACD](https://zkevm.polygonscan.com//address/0xD87F44Df0159DC78029AB9CA7D7e57E7249F5ACD#code) | [20230316-l2-ve-delegation-proxy](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230316-l2-ve-delegation-proxy)             |
| ProtocolIdRegistry                             | [0x6CaD2ea22BFA7F4C14Aae92E47F510Cd5C509bc7](https://zkevm.polygonscan.com//address/0x6CaD2ea22BFA7F4C14Aae92E47F510Cd5C509bc7#code) | [20230223-protocol-id-registry](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230223-protocol-id-registry)                 |
| WETH                                           | [0x4F9A0e7FD2Bf6067db6994CF12E4495Df938E6e9](https://zkevm.polygonscan.com//address/0x4F9A0e7FD2Bf6067db6994CF12E4495Df938E6e9#code) | [00000000-tokens](https://github.com/balancer/balancer-deployments/blob/master/tasks/00000000-tokens)                                             |
    
    
# Deprecated Contracts

These deployments were in use at some point, and may still be in active operation, for example in the case of pools created with old factories.  In general it's better to interact with newer versions when possible.

#### If you can only find the contract you are looking for in the deprecated section and it is not an old pool, try checking the deployments tasks to find it or ask in the Discord before using a deprecated contract.

    
| Contract                         | Address                                                                                                                              | Deployment                                                                                                                                  |
|:---------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------|
| ComposableStablePoolFactory (v4) | [0x8eA89804145c007e7D226001A96955ad53836087](https://zkevm.polygonscan.com//address/0x8eA89804145c007e7D226001A96955ad53836087#code) | [20230320-composable-stable-pool-v4](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230320-composable-stable-pool-v4) |
| MockComposableStablePool (v4)    | [0x6f5F794A3CeF904b8517C4c311DE2FA837Ff24a0](https://zkevm.polygonscan.com//address/0x6f5F794A3CeF904b8517C4c311DE2FA837Ff24a0#code) | [20230320-composable-stable-pool-v4](https://github.com/balancer/balancer-deployments/blob/master/tasks/20230320-composable-stable-pool-v4) |
    
<style scoped>
table {
    display: table;
    width: 100%;
}
table th:first-of-type, td:first-of-type {
    width: 30%;
}
table th:nth-of-type(2) {
    width: 40%;
}
td {
    max-width: 0;
    overflow: hidden;
}
</style>

