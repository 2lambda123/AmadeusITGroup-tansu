<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@amadeus-it-group/tansu](./tansu.md) &gt; [Store](./tansu.store.md) &gt; [equal](./tansu.store.equal.md)

## Store.equal() method

Compares two values and returns true if they are equal. It is called when setting a new value to avoid doing anything (such as notifying subscribers) if the value did not change. The default logic is to return false if `a` is a function or an object, or if `a` and `b` are different according to `Object.is`<!-- -->. This method can be overridden by subclasses to change the logic.

**Signature:**

```typescript
protected equal(a: T, b: T): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  a | T | First value to compare. |
|  b | T | Second value to compare. |

**Returns:**

boolean

true if a and b are considered equal.

## Remarks

For backward compatibility, the default implementation calls the deprecated [Store.notEqual()](./tansu.store.notequal.md) method and returns the negation of its return value.
