# LayerInstance\.AutoLayerTiles Property

[Home](../../../README.md)

**Containing Type**: [LayerInstance](../README.md)

**Assembly**: LDtkMonogame\.dll

  
 An array containing all tiles generated by Auto\-layer rules\. The array is already sorted in display order \(ie\. 1st tile is beneath 2nd, which is beneath 3rd etc\.\)\.  Note: if multiple tiles are stacked in the same cell as the result of different rules, all tiles behind opaque ones will be discarded\. 

```csharp
[System.Text.Json.Serialization.JsonPropertyName("autoLayerTiles")]
public LDtk.TileInstance[] AutoLayerTiles { get; set; }
```

### Property Value

[TileInstance](../../TileInstance/README.md)\[\]

### Attributes

* [JsonPropertyNameAttribute](https://docs.microsoft.com/en-us/dotnet/api/system.text.json.serialization.jsonpropertynameattribute)

