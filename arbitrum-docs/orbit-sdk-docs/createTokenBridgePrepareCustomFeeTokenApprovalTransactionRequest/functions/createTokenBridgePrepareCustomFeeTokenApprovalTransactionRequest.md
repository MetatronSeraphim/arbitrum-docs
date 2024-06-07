---
layout: docs
sidebar: false
toc_max_heading_level: 5
---

```ts
function createTokenBridgePrepareCustomFeeTokenApprovalTransactionRequest(
  __namedParameters: object,
): Promise<any>;
```

Creates a Token Bridge prepare custom fee token approval transaction request
with specified parameters. This function returns a Request object
containing the approval transaction details.

## Parameters

| Parameter                                              | Type              | Description                                                                                                                                |
| :----------------------------------------------------- | :---------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| `__namedParameters`                                    | `object`          | -                                                                                                                                          |
| `__namedParameters.amount`?                            | `bigint`          | -                                                                                                                                          |
| `__namedParameters.nativeToken`                        | \`0x$\{string\}\` | -                                                                                                                                          |
| `__namedParameters.owner`                              | \`0x$\{string\}\` | -                                                                                                                                          |
| `__namedParameters.publicClient`                       | `object`          | -                                                                                                                                          |
| `__namedParameters.tokenBridgeCreatorAddressOverride`? | \`0x$\{string\}\` | Specifies a custom address for the TokenBridgeCreator. By default, the address will be automatically detected based on the provided chain. |

## Returns

`Promise`\<`any`\>

## Source

[src/createTokenBridgePrepareCustomFeeTokenApprovalTransactionRequest.ts:24](https://github.com/OffchainLabs/arbitrum-orbit-sdk/blob/9d5595a042e42f7d6b9af10a84816c98ea30f330/src/createTokenBridgePrepareCustomFeeTokenApprovalTransactionRequest.ts#L24)