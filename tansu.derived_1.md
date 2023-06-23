<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@amadeus-it-group/tansu](./tansu.md) &gt; [derived](./tansu.derived_1.md)

## derived() function

**Signature:**

```typescript
export declare function derived<T, S extends StoresInput>(stores: S, options: SyncDeriveFn<T, S> | SyncDeriveOptions<T, S>, initialValue?: T): ReadableSignal<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  stores | S |  |
|  options | SyncDeriveFn&lt;T, S&gt; \| SyncDeriveOptions&lt;T, S&gt; |  |
|  initialValue | T | _(Optional)_ |

**Returns:**

[ReadableSignal](./tansu.readablesignal.md)<!-- -->&lt;T&gt;
