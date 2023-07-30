# WebIcons-StreamDeckIconPack
This iconpack contains web url icons

![](https://raw.githubusercontent.com/L1cardo/WebIcons-StreamDeckIconPack/main/cn.licardo.webicons.sdIconPack/previews/Frame1.png)

## How to pack an iconpack

https://docs.elgato.com/sdk/icon-packs/packaging

### Creating a .streamDeckIconPack file
Here is how you can use the DistributionTool to export the com.elgato.hello.sdIconPack icon pack:
- macOS

```zsh
DistributionTool -b -i com.elgato.hello.sdIconPack -o ~/Desktop/
```

- Windows

```powershell
.\DistributionTool.exe -b -i com.elgato.hello.sdIconPack -o .\
```

If the export is successful, you should see the following:

```powershell
Validating and export the icon pack com.elgato.hello.sdIconPack
The icon pack has been successfully exported
```
