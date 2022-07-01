[@alch/alchemy-sdk](../README.md) / [Exports](../modules.md) / GetBaseNftsForCollectionOptions

# Interface: GetBaseNftsForCollectionOptions

Optional parameters object for the [getNftsForCollection](../modules.md#getnftsforcollection) and
[getNftsForCollectionIterator](../modules.md#getnftsforcollectioniterator) functions.

This interface is used to fetch NFTs without their associated metadata. To
get Nfts with their associated metadata, use [GetNftsForCollectionOptions](GetNftsForCollectionOptions.md).

## Table of contents

### Properties

- [omitMetadata](GetBaseNftsForCollectionOptions.md#omitmetadata)
- [pageKey](GetBaseNftsForCollectionOptions.md#pagekey)

## Properties

### omitMetadata

• **omitMetadata**: ``false``

Optional boolean flag to omit NFT metadata. Defaults to `false`.

#### Defined in

[src/types/types.ts:443](https://github.com/alchemyplatform/alchemy-sdk-js/blob/9fe1224/src/types/types.ts#L443)

___

### pageKey

• `Optional` **pageKey**: `string`

Optional page key from an existing [CollectionBaseNftsResponse](CollectionBaseNftsResponse.md) or
[CollectionNftsResponse](CollectionNftsResponse.md)to use for pagination.

#### Defined in

[src/types/types.ts:440](https://github.com/alchemyplatform/alchemy-sdk-js/blob/9fe1224/src/types/types.ts#L440)
