<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@amadeus-it-group/tansu](./tansu.md) &gt; [Store](./tansu.store.md) &gt; [update](./tansu.store.update.md)

## Store.update() method

Updates store's state by using an [Updater](./tansu.updater.md) function. Equivalent of [Writable.update()](./tansu.writable.update.md)<!-- -->, but internal to the store.

**Signature:**

```typescript
protected update(updater: Updater<T>): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  updater | [Updater](./tansu.updater.md)<!-- -->&lt;T&gt; | a function that takes the current state as an argument and returns the new state. |

**Returns:**

void
