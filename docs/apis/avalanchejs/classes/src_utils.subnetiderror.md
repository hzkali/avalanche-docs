[avalanche](../README.md) › [src/utils](../modules/src_utils.md) › [SubnetIdError](src_utils.subnetiderror.md)

# Class: SubnetIdError

## Hierarchy

  ↳ [AvalancheError](src_utils.avalancheerror.md)

  ↳ **SubnetIdError**

## Index

### Constructors

* [constructor](src_utils.subnetiderror.md#constructor)

### Properties

* [errorCode](src_utils.subnetiderror.md#errorcode)
* [message](src_utils.subnetiderror.md#message)
* [name](src_utils.subnetiderror.md#name)
* [stack](src_utils.subnetiderror.md#optional-stack)

### Methods

* [getCode](src_utils.subnetiderror.md#getcode)

## Constructors

###  constructor

\+ **new SubnetIdError**(`m`: string): *[SubnetIdError](src_utils.subnetiderror.md)*

*Overrides [AvalancheError](src_utils.avalancheerror.md).[constructor](src_utils.avalancheerror.md#constructor)*

*Defined in [src/utils/errors.ts:354](https://github.com/ava-labs/avalanchejs/blob/4e59193/src/utils/errors.ts#L354)*

**Parameters:**

Name | Type |
------ | ------ |
`m` | string |

**Returns:** *[SubnetIdError](src_utils.subnetiderror.md)*

## Properties

###  errorCode

• **errorCode**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[errorCode](src_utils.avalancheerror.md#errorcode)*

*Defined in [src/utils/errors.ts:48](https://github.com/ava-labs/avalanchejs/blob/4e59193/src/utils/errors.ts#L48)*

___

###  message

• **message**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1023

___

###  name

• **name**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1022

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1024

## Methods

###  getCode

▸ **getCode**(): *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[getCode](src_utils.avalancheerror.md#getcode)*

*Defined in [src/utils/errors.ts:55](https://github.com/ava-labs/avalanchejs/blob/4e59193/src/utils/errors.ts#L55)*

**Returns:** *string*
