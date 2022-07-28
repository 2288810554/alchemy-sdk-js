[alchemy-sdk](../README.md) / [Exports](../modules.md) / DeployResult

# Interface: DeployResult

The response object for the {@link findContractDeployer} function.

## Table of contents

### Properties

- [blockNumber](DeployResult.md#blocknumber)
- [deployerAddress](DeployResult.md#deployeraddress)

## Properties

### blockNumber

• `Readonly` **blockNumber**: `number`

The block number the contract was deployed in.

#### Defined in

[src/types/types.ts:573](https://github.com/alchemyplatform/alchemy-sdk-js/blob/6507682/src/types/types.ts#L573)

___

### deployerAddress

• `Optional` `Readonly` **deployerAddress**: `string`

The address of the contract deployer, if it is available.

#### Defined in

[src/types/types.ts:570](https://github.com/alchemyplatform/alchemy-sdk-js/blob/6507682/src/types/types.ts#L570)
