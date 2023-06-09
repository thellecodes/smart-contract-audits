### Index

- [BaseV2GaugeManager](BaseV2GaugeManager.md)
  - [addGauge](BaseV2GaugeManager.md#function-addgauge)
  - [removeGauge](BaseV2GaugeManager.md#function-removegauge)
  - [changebHermesGaugeOwner](BaseV2GaugeManager.md#function-changebhermesgaugeowner)
  - [addGaugeFactory()](BaseV2GaugeManager.md#function-addgaugefactory)
  - [removeGaugeFactory](BaseV2GaugeManager.md#function-removegaugefactory)
- [BaseV2GaugeFactory](BaseV2GaugeFactory.md)
  - [addBribeToGauge(BaseV2Gauge gauge, address bribeToken)](BaseV2GaugeFactory.md#function-addbribetogaugebasev2gauge-gauge-address-bribetoken)
  - [createGauge(address strategy, byte[] data)](BaseV2GaugeFactory.md#function-creategaugeaddress-strategy-byte-data)
  - [newEpoch()](BaseV2GaugeFactory.md#function-newepoch)
  - [newEpoch(uint256 start, uint256 end)](BaseV2GaugeFactory.md#function-newepochuint256-start-uint256-end)
  - [removeBribeFromGauge(BaseV2Gauge gauge, address bribeToken)](BaseV2GaugeFactory.md#function-removebribefromgaugebasev2gauge-gauge-address-bribetoken)
  - [removeGauge(BaseV2Gauge gauge)](BaseV2GaugeFactory.md#function-removegaugebasev2gauge-gauge)
- [UniswapV3GaugeFactory](UniswapV3GaugeFactory.md)
  - [setMinimumWidth(address gauge, uint24 minimumWidth)](UniswapV3GaugeFactory.md#function-setminimumwidthaddress-gauge-uint24-minimumwidth)
- [BribesFactory](BribesFactory.md)
  - [addGaugetoFlywheel(address gauge, address bribeToken)](BribesFactory.md#function-addgaugetoflywheeladdress-gauge-address-bribetoken)
  - [createBribeFlywheel(address bribeToken)](BribesFactory.md#function-createbribeflywheeladdress-bribetoken)