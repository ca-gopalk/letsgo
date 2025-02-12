[@letsgo/constants](../README.md) / DBSettings

# Interface: DBSettings

Parameters that control the creation of the _database_ component.

## Table of contents

### Properties

- [getTableName](DBSettings.md#gettablename)

## Properties

### getTableName

• **getTableName**: (`deployment`: `string`) => `string`

#### Type declaration

▸ (`deployment`): `string`

Returns the name of the DynamoDB table to create.

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `deployment` | `string` | LetsGo deployment name |

##### Returns

`string`

DynamoDB table name

#### Defined in

[index.ts:575](https://github.com/47chapters/letsgo/blob/11c7e19/packages/constants/src/index.ts#L575)
