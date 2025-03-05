# Mod Support Matrix

## How to fill out this table

You may:

- Add a new device to the table, by appending a new row to the table. (You can get device codename from `adb shell getprop ro.product.name`)
- Add a new mod to the table, by appending a new column to the table. (Make sure you have modify all the rows to add the column!)
- Fill out the table with the compatibility of the mod on the device, by marking the cell with
    - a checkmark (✅) if the mod is compatible, 
    - or a cross (❌) if the mod is fully not compatible (and file an issue/link to the issue). 
    - If the mod is not tested (not included in your modpack/you do not install this mod), mark the cell with a question mark (?).
    - a asterisk (*️⃣) if the mod is working, but have missing features and/or have graphical glitches (and file an issue/link to the issue).
- If applicable, you may want to mention what additional drivers/plugins rather than the one vendor provides, are in use (such as turnip drivers, ANGLE, etc.) in the "Additional Drivers/Plugins in use" column.
- If applicable, you should add a file named `*device_codename*.md`, to provide additional information, and put the link in the last column.

## The Support Matrix

<div style="overflow-x: auto;">

| **Device (Codename)** | **SoC** | **GPU** | **OS** | **Additional Drivers/Plugins in use** | **MobileGlues** | **Minecraft** | **ModLoader** | **Sodium** | **Iris** | **Indium** | **Xaero's Minimap** | **Xaero's World Map** |  **Create** | **TaCZ** | **[ETF]Entity Texture Features** | **Report** |
|------------------------|---------|---------|--------|--------|-----------------|---------------|---------------|------------|---------|---------------------|----------------------|-------------|-------------|---------------|---------------|---------------|
| Xiaomi 15 (dada) | Snapdragon 8 Elite | Adreno 830 | Android 15 | N/A | 1.1.0.1 | 1.20.1 | Fabric 0.16.10 | ✅(0.5.11) | ✅(1.7.2) | ✅(1.0.34) |  ✅(25.0.0) | ✅(1.39.2) | ✅(fabric-0.5.1-j) | ✅(1.0.2) | ? | [dada.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/DeviceReports/dada.md) |
| vivo X200 Pro (PD2405) | Dimensity 9400 | Mali-G925-Immortalis MC12 | Android 15 | ANGLE | 1.1.0.1 | 1.20.1 | Fabric 0.16.10 | ✅(0.5.11) | ✅(1.7.5) | ✅(1.0.36) | ✅(25.0.0) | ✅(1.39.4) | ✅(fabric-0.5.1-j)<sup>1<sup> | ✅(1.0.2) | ? | [PD2405.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/DeviceReports/PD2405.md) |
| Xiaomi Mi CC9 Pro (tucana) | Snapdragon 730G | OpenCL 2.0 Adreno(TM) 618 | Android 11 | N/A | 1.1.0.1 | 1.21.4 | Fabric 0.16.10 | ✅(0.6.6) | ✅(1.8.5) | ? | ✅(25.0.0) | ✅(1.39.2) | ? | ? | ✅(6.2.10) | [tucana.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/DeviceReports/tucana.md) |
<div>