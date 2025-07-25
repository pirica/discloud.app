[**Documentation**](../../README.md)

***

[Documentation](../../packages.md) / [discloud.app](../README.md) / ApiAppManagerRestartedAll

# Interface: ApiAppManagerRestartedAll

Defined in: [packages/api-types/rest/v2/app.ts:105](https://github.com/discloud/discloud.app/blob/ff86a7704bdfa4b9011141068419f0a48ab50b8b/packages/api-types/rest/v2/app.ts#L105)

## Extends

- [`Omit`](https://www.typescriptlang.org/docs/handbook/utility-types.html#omittype-keys)\<[`ApiAppManager`](ApiAppManager.md), `"alreadyOnline"`\>

## Properties

### alreadyInProcess

> **alreadyInProcess**: `string`[]

Defined in: [packages/api-types/rest/v2/app.ts:87](https://github.com/discloud/discloud.app/blob/ff86a7704bdfa4b9011141068419f0a48ab50b8b/packages/api-types/rest/v2/app.ts#L87)

Which of your applications are currently `processing`

#### Inherited from

`Omit.alreadyInProcess`

***

### alreadyOffline

> **alreadyOffline**: `string`[]

Defined in: [packages/api-types/rest/v2/app.ts:91](https://github.com/discloud/discloud.app/blob/ff86a7704bdfa4b9011141068419f0a48ab50b8b/packages/api-types/rest/v2/app.ts#L91)

Which of your applications are currently `offline`

#### Inherited from

`Omit.alreadyOffline`

***

### restarted

> **restarted**: `string`[]

Defined in: [packages/api-types/rest/v2/app.ts:109](https://github.com/discloud/discloud.app/blob/ff86a7704bdfa4b9011141068419f0a48ab50b8b/packages/api-types/rest/v2/app.ts#L109)

Which of your applications have been `restarted`
