<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [PopulatableLiquity](./lib-base.populatableliquity.md) &gt; [redeemLUSD](./lib-base.populatableliquity.redeemlusd.md)

## PopulatableLiquity.redeemLUSD() method

Redeem LUSD to native currency (e.g. Ether) at face value.

<b>Signature:</b>

```typescript
redeemLUSD(amount: Decimalish): Promise<PopulatedLiquityTransaction<P, SentLiquityTransaction<S, LiquityReceipt<R, RedemptionDetails>>>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./decimal.decimalish.md) | Amount of LUSD to be redeemed. |

<b>Returns:</b>

Promise&lt;[PopulatedLiquityTransaction](./lib-base.populatedliquitytransaction.md)<!-- -->&lt;P, [SentLiquityTransaction](./lib-base.sentliquitytransaction.md)<!-- -->&lt;S, [LiquityReceipt](./lib-base.liquityreceipt.md)<!-- -->&lt;R, [RedemptionDetails](./lib-base.redemptiondetails.md)<!-- -->&gt;&gt;&gt;&gt;

