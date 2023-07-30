# WebIcons-StreamDeckIconPack
This iconpack contains web url icons

![](https://raw.githubusercontent.com/L1cardo/WebIcons-StreamDeckIconPack/main/cn.licardo.webicons.sdIconPack/previews/Frame1.png)

## How to pack an iconpack

https://docs.elgato.com/sdk/icon-packs/packaging

### Creating a .streamDeckIconPack file
Here is how you can use the DistributionTool to export the com.elgato.hello.sdIconPack icon pack:
- macOS

```bash
DistributionTool -b -i com.elgato.hello.sdIconPack -o ~/Desktop/
```

- Windows

```bash
DistributionTool.exe -b -i com.elgato.hello.sdIconPack -o Release
```

If the export is successful, you should see the following:

```bash
Validating and export the icon pack com.elgato.hello.sdIconPack
The icon pack has been successfully exported
```
