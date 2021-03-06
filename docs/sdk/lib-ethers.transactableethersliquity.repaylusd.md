<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [TransactableEthersLiquity](./lib-ethers.transactableethersliquity.md) &gt; [repayLUSD](./lib-ethers.transactableethersliquity.repaylusd.md)

## TransactableEthersLiquity.repayLUSD() method

Adjust existing Trove by repaying some of its debt.

<b>Signature:</b>

```typescript
repayLUSD(amount: Decimalish, overrides?: EthersTransactionOverrides): Promise<TroveAdjustmentDetails>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./decimal.decimalish.md) | The amount of LUSD to repay. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[TroveAdjustmentDetails](./lib-base.troveadjustmentdetails.md)<!-- -->&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure.

## Remarks

Equivalent to:

```typescript
adjustTrove({ repayLUSD: amount })

```

