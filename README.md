# TgaSharp
Port of [TGASharpLib](https://github.com/ALEXGREENALEX/TGASharpLib) for .NET Core.

## Renamed Objects
The following objects have been renamed in code to more closely follow conventions. References will need to be updated in projects using this library.

| Object                   | Original          | Renamed                  |
| ------------------------ | ----------------- | ------------------------ |
| Namespace                | `TGASharpLib`     | `Crews.Utility.TgaSharp` |
| Image origin enumerable  | `TgaImgOrigin`    | `TgaImageOrigin`         |
| Alpha type enumerable    | `TgaAttrType`     | `TgaAlphaType`           |
| Color map info class     | `TgaColorMapSpec` | `TgaColorMapInfo`        |
| Developer entry class    | `TgaDevEntry`     | `TgaDeveloperEntry`      |
| Image info class         | `TgaImageSpec`    | `TgaImageInfo`           |
| Image or color map class | `TgaImgOrColMap`  | `TgaImageOrColorMap`     |
| Developer area class     | `TgaDevArea`      | `TgaDeveloperArea`       |
| Extension area class     | `TgaExtArea`      | `TgaExtensionArea`       |
| Byte conversion class    | `BitConverterExt` | `ByteConverter`          |
