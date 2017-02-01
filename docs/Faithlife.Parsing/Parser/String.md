# Parser.String method (1 of 3)

Maps a successfully parsed collection of characters into a successfully parsed string.

```csharp
public static IParser<string> String(this IParser<IEnumerable<char>> parser)
```

## See Also

* interface [IParser&lt;T&gt;](../IParser-1.md)
* class [Parser](../Parser.md)
* namespace [Faithlife.Parsing](../../Faithlife.Parsing.md)

---

# Parser.String method (2 of 3)

Parses the specified string using ordinal (case-sensitive) comparison.

```csharp
public static IParser<string> String(string text)
```

## See Also

* interface [IParser&lt;T&gt;](../IParser-1.md)
* class [Parser](../Parser.md)
* namespace [Faithlife.Parsing](../../Faithlife.Parsing.md)

---

# Parser.String method (3 of 3)

Parses the specified string using the specified string comparison.

```csharp
public static IParser<string> String(string text, StringComparison comparison)
```

## See Also

* interface [IParser&lt;T&gt;](../IParser-1.md)
* class [Parser](../Parser.md)
* namespace [Faithlife.Parsing](../../Faithlife.Parsing.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Parsing.dll -->