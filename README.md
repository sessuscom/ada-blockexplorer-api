# ADA/Cardano Blockchain Block Explorer api client

It supports the following runtimes

- .NET Standard 1.4
- .NET Standard 2.0

   
## Examples

### Get Transaction Info
```csharp
var adaBlockExplorer = new AdaBlockExplorerClient()
var trasaction = await service.GetTransaction("02712610f05e284db32c37eda9c1212f0a719585a0b4f8f822af669eb2b3d384");
```

## NuGet
    PM> Install-Package GV.Ada.BlockExplorer

# License
The AdaBlockExplorerClient library is licensed under the MIT license.
