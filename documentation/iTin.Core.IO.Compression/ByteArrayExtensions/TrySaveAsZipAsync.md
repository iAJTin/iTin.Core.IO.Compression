# ByteArrayExtensions.TrySaveAsZipAsync method (1 of 2)

Try to Create asynchronously a zip file with specified element.

```csharp
public static Task<IResult> TrySaveAsZipAsync(this byte[] item, string itemExtension, 
    string outputPath, CancellationToken cancellationToken = default)
```

| parameter | description |
| --- | --- |
| item | Element to compress. |
| itemExtension | File elements extension. |
| outputPath | Zip output path. |
| cancellationToken | A cancellation token that can be used by other objects or threads to receive notice of cancellation. |

## Return Value

A IResult than contains zipped file.

## See Also

* class [ByteArrayExtensions](../ByteArrayExtensions.md)
* namespace [iTin.Core.IO.Compression](../../iTin.Core.IO.Compression.md)

---

# ByteArrayExtensions.TrySaveAsZipAsync method (2 of 2)

Try to Create asynchronously a zip file with specified elements.

```csharp
public static Task<IResult> TrySaveAsZipAsync(this IEnumerable<byte[]> items, 
    string itemsExtension, string outputPath, CancellationToken cancellationToken = default)
```

| parameter | description |
| --- | --- |
| items | Element to compress. |
| itemsExtension | File elements extension. |
| outputPath | Zip output path. |
| cancellationToken | A cancellation token that can be used by other objects or threads to receive notice of cancellation. |

## Return Value

A String than contains the path to created file.

## See Also

* class [ByteArrayExtensions](../ByteArrayExtensions.md)
* namespace [iTin.Core.IO.Compression](../../iTin.Core.IO.Compression.md)

<!-- DO NOT EDIT: generated by xmldocmd for iTin.Core.IO.Compression.dll -->
