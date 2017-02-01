# Parser.Repeat&lt;T&gt; method (1 of 2)

Succeeds if the parser succeeds the specified number of times. The value is a collection of the parsed items.

```csharp
public static IParser<IReadOnlyList<T>> Repeat<T>(this IParser<T> parser, int exactly)
```

## See Also

* interface [IParser&lt;T&gt;](../IParser-1.md)
* class [Parser](../Parser.md)
* namespace [Faithlife.Parsing](../../Faithlife.Parsing.md)

---

# Parser.Repeat&lt;T&gt; method (2 of 2)

Succeeds if the parser succeeds the specified number of times. The value is a collection of the parsed items.

```csharp
public static IParser<IReadOnlyList<T>> Repeat<T>(this IParser<T> parser, int atLeast, int atMost)
```

## See Also

* interface [IParser&lt;T&gt;](../IParser-1.md)
* class [Parser](../Parser.md)
* namespace [Faithlife.Parsing](../../Faithlife.Parsing.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Parsing.dll -->