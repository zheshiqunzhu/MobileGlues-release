# Compatible Mods

- Sodium (Fabric) / Embeddium (NeoForge)
- Iris / OptiFine <sup>1</sup>
- Indium
- Distant Horizon
- JourneyMap
- Xaero's Minimap
- Xaero's World Map (has color issues under 0.5x zoom)
- Create 0.5.1j (Fabric / NeoForge, with flywheel batching/instancing backend supported <sup>2</sup>)
- Timeless and Classics Zero (aka. TaCZ, Fabric)

<sup>1</sup> Regarding shader compatibility, please refer to [CompatibleShaders.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/CompatibleShaders.md)

<sup>2</sup> Some Mali GPUs may have rendering issues with Create's flywheel instancing backend. This is caused by a bug in Mali's ES driver. If you encounter rendering issues, please turn on ANGLE in MobileGlues app and restart launcher, or switch to other backends (using `/flywheel backend batching` or `/flywheel backend none`).