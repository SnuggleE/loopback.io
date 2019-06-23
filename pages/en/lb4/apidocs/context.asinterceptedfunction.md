---
lang: en
title: 'API docs: context.asinterceptedfunction'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.asinterceptedfunction.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [AsInterceptedFunction](./context.asinterceptedfunction.md)

## AsInterceptedFunction type

The intercepted variant of a function to return `ValueOrPromise<T>`<!-- -->. If `T` is not a function, the type is `T`<!-- -->.

<b>Signature:</b>

```typescript
export declare type AsInterceptedFunction<T> = T extends (...args: InvocationArgs) => infer R ? (...args: InvocationArgs) => AsValueOrPromise<R> : T;
```
