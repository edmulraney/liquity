<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [TransactableEthersLiquity](./lib-ethers.transactableethersliquity.md) &gt; [sendLQTY](./lib-ethers.transactableethersliquity.sendlqty.md)

## TransactableEthersLiquity.sendLQTY() method

Send LQTY tokens to an address.

<b>Signature:</b>

```typescript
sendLQTY(toAddress: string, amount: Decimalish, overrides?: EthersTransactionOverrides): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  toAddress | string | Address of receipient. |
|  amount | [Decimalish](./decimal.decimalish.md) | Amount of LQTY to send. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;void&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure.

