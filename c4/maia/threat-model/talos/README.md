### Index

- [factories](factories)
  - [TalosStrategyStakedFactory](factories/TalosStrategyStakedFactory.md)
    - [constructor](factories/TalosStrategyStakedFactory.md#function-constructor)
  - [TalosStrategyVanillaFactory](factories/TalosStrategyVanillaFactory.md)

  - [TalosBaseStrategyFactory](factories/TalosBaseStrategyFactory.md)
    - [createTalosBaseStrategy(IUniswapV3Pool pool, ITalosOptimizer optimizer, address strategyManager, byte[] data)](factories/TalosBaseStrategyFactory.md#function-createtalosbasestrategyiuniswapv3pool-pool-italosoptimizer-optimizer-address-strategymanager-byte-data)
  - [OptimizerFactory](factories/OptimizerFactory.md)
    - [createTalosOptimizer(uint32 \_twapDuration, int24 \_maxTwapDeviation, int24 \_tickRangeMultiplier, uint24 \_priceImpactPercentage, uint256 \_maxTotalSupply, address owner)](factories/OptimizerFactory.md#function-createtalosoptimizeruint32-_twapduration-int24-_maxtwapdeviation-int24-_tickrangemultiplier-uint24-_priceimpactpercentage-uint256-_maxtotalsupply-address-owner)
  - [BoostAggregatorFactory](factories/BoostAggregatorFactory.md)
    - [createBoostAggregator(address owner)](factories/BoostAggregatorFactory.md#function-createboostaggregatoraddress-owner)
- [boost-aggregator](boost-aggregator)
  - [BoostAggregator](boost-aggregator/BoostAggregator.md)
    - [addWhitelistedAddress(address user)](boost-aggregator/BoostAggregator.md#function-addwhitelistedaddressaddress-user)
    - [decrementGaugesBoostIndexed(uint256 boost, uint256 offset, uint256 num)](boost-aggregator/BoostAggregator.md#function-decrementgaugesboostindexeduint256-boost-uint256-offset-uint256-num)
    - [depositAndStake(uint256 tokenId)](boost-aggregator/BoostAggregator.md#function-depositandstakeuint256-tokenid)
    - [removeWhitelistedAddress(address user)](boost-aggregator/BoostAggregator.md#function-removewhitelistedaddressaddress-user)
    - [setOwnRewardsDepot(address rewardsDepot)](boost-aggregator/BoostAggregator.md#function-setownrewardsdepotaddress-rewardsdepot)
    - [setProtocolFee(uint256 \_protocolFee)](boost-aggregator/BoostAggregator.md#function-setprotocolfeeuint256-_protocolfee)
    - [unstakeAndWithdraw(uint256 tokenId)](boost-aggregator/BoostAggregator.md#function-unstakeandwithdrawuint256-tokenid)
    - [withdrawAllGaugeBoost(address to)](boost-aggregator/BoostAggregator.md#function-withdrawallgaugeboostaddress-to)
    - [withdrawGaugeBoost(address to, uint256 amount)](boost-aggregator/BoostAggregator.md#function-withdrawgaugeboostaddress-to-uint256-amount)
    - [withdrawProtocolFees(address to)](boost-aggregator/BoostAggregator.md#function-withdrawprotocolfeesaddress-to)
- [TalosManager](TalosManager.md)
  - [performUpkeep(byte[] None)](TalosManager.md#function-performupkeepbyte-none)
- [base](base)
  - [TalosBaseStrategy](base/TalosBaseStrategy.md)
    - [init](base/TalosBaseStrategy.md#function-init)
    - [deposit](base/TalosBaseStrategy.md#function-deposit)
    - [redeem](base/TalosBaseStrategy.md#function-redeem)
    - [rerange](base/TalosBaseStrategy.md#function-rerange)
    - [rebalance](base/TalosBaseStrategy.md#function-rebalance)
    - [uniswapV3SwapCallback](base/TalosBaseStrategy.md#function-uniswapv3swapcallback)
- [TalosOptimizer](TalosOptimizer.md)
  - [setMaxTotalSupply(uint256 \_maxTotalSupply)](TalosOptimizer.md#function-setmaxtotalsupplyuint256-_maxtotalsupply)
  - [setMaxTwapDeviation(int24 \_maxTwapDeviation)](TalosOptimizer.md#function-setmaxtwapdeviationint24-_maxtwapdeviation)
  - [setPriceImpact(uint24 \_priceImpactPercentage)](TalosOptimizer.md#function-setpriceimpactuint24-_priceimpactpercentage)
  - [setTickRange(int24 \_tickRangeMultiplier)](TalosOptimizer.md#function-settickrangeint24-_tickrangemultiplier)
  - [setTwapDuration(uint32 \_twapDuration)](TalosOptimizer.md#function-settwapdurationuint32-_twapduration)