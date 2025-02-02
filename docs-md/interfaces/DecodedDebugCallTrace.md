[alchemy-sdk](../README.md) / [Exports](../modules.md) / DecodedDebugCallTrace

# Interface: DecodedDebugCallTrace

Decoded representation of the call trace that is part of a
[SimulationCallTrace](SimulationCallTrace.md).

## Table of contents

### Properties

- [authority](DecodedDebugCallTrace.md#authority)
- [inputs](DecodedDebugCallTrace.md#inputs)
- [methodName](DecodedDebugCallTrace.md#methodname)
- [outputs](DecodedDebugCallTrace.md#outputs)

## Properties

### authority

• **authority**: [`ETHERSCAN`](../enums/DecodingAuthority.md#etherscan)

The source used to provide the decoded call trace.

#### Defined in

[src/types/types.ts:961](https://github.com/alchemyplatform/alchemy-sdk-js/blob/44aa50c/src/types/types.ts#L961)

___

### inputs

• **inputs**: [`DecodedCallParam`](DecodedCallParam.md)[]

Method inputs.

#### Defined in

[src/types/types.ts:957](https://github.com/alchemyplatform/alchemy-sdk-js/blob/44aa50c/src/types/types.ts#L957)

___

### methodName

• **methodName**: `string`

The smart contract method called.

#### Defined in

[src/types/types.ts:955](https://github.com/alchemyplatform/alchemy-sdk-js/blob/44aa50c/src/types/types.ts#L955)

___

### outputs

• **outputs**: [`DecodedCallParam`](DecodedCallParam.md)[]

Method outputs.

#### Defined in

[src/types/types.ts:959](https://github.com/alchemyplatform/alchemy-sdk-js/blob/44aa50c/src/types/types.ts#L959)
