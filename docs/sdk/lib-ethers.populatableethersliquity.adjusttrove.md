<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [PopulatableEthersLiquity](./lib-ethers.populatableethersliquity.md) &gt; [adjustTrove](./lib-ethers.populatableethersliquity.adjusttrove.md)

## PopulatableEthersLiquity.adjustTrove() method

Adjust existing Trove by changing its collateral, debt, or both.

<b>Signature:</b>

```typescript
adjustTrove(params: TroveAdjustmentParams<Decimalish>, overrides?: EthersTransactionOverrides): Promise<PopulatedEthersLiquityTransaction<TroveAdjustmentDetails>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  params | [TroveAdjustmentParams](./lib-base.troveadjustmentparams.md)<!-- -->&lt;[Decimalish](./decimal.decimalish.md)<!-- -->&gt; | Parameters of the adjustment. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[PopulatedEthersLiquityTransaction](./lib-ethers.populatedethersliquitytransaction.md)<!-- -->&lt;[TroveAdjustmentDetails](./lib-base.troveadjustmentdetails.md)<!-- -->&gt;&gt;

## Remarks

The transaction will fail if the Trove's debt would fall below [LUSD\_LIQUIDATION\_RESERVE](./lib-base.lusd_liquidation_reserve.md)<!-- -->.

