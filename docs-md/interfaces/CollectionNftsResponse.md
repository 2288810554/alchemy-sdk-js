[@alch/alchemy-sdk](../README.md) / [Exports](../modules.md) / CollectionNftsResponse

# Interface: CollectionNftsResponse

The response object for the [getNftsForCollection](../modules.md#getnftsforcollection) function. The object
contains the NFTs with metadata inside the collection.

## Table of contents

### Properties

- [nfts](CollectionNftsResponse.md#nfts)
- [pageKey](CollectionNftsResponse.md#pagekey)

## Properties

### nfts

• **nfts**: [`Nft`](Nft.md)[]

An array of NFTs with metadata.

#### Defined in

[src/types/types.ts:471](https://github.com/alchemyplatform/alchemy-sdk-js/blob/9fe1224/src/types/types.ts#L471)

___

### pageKey

• `Optional` **pageKey**: `string`

Pagination token that can be passed into another request to fetch the next
NFTs. If there is no page key, then there are no more NFTs to fetch.

#### Defined in

[src/types/types.ts:477](https://github.com/alchemyplatform/alchemy-sdk-js/blob/9fe1224/src/types/types.ts#L477)
