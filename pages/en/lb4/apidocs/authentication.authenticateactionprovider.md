---
lang: en
title: 'API docs: authentication.authenticateactionprovider'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/authentication
permalink: /doc/en/lb4/apidocs.authentication.authenticateactionprovider.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authentication](./authentication.md) &gt; [AuthenticateActionProvider](./authentication.authenticateactionprovider.md)

## AuthenticateActionProvider class

Provides the authentication action for a sequence

<b>Signature:</b>

```typescript
export declare class AuthenticateActionProvider implements Provider<AuthenticateFn> 
```

## Example

`context.bind('authentication.actions.authenticate').toProvider(AuthenticateActionProvider)`

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(getStrategy, setCurrentUser)](./authentication.authenticateactionprovider._constructor_.md) |  | Constructs a new instance of the <code>AuthenticateActionProvider</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [getStrategy](./authentication.authenticateactionprovider.getstrategy.md) |  | <code>Getter&lt;AuthenticationStrategy&gt;</code> |  |
|  [setCurrentUser](./authentication.authenticateactionprovider.setcurrentuser.md) |  | <code>Setter&lt;UserProfile&gt;</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [action(request)](./authentication.authenticateactionprovider.action.md) |  | The implementation of authenticate() sequence action. |
|  [value()](./authentication.authenticateactionprovider.value.md) |  |  |

