# awesome-vrm

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, libraries, SDKs, and specifications for developing with **VRM** and **VRoid** — the open file format and ecosystem for humanoid 3D avatars.

This list is aimed at **developers**: it focuses on the VRM format, avatar pipelines, and the libraries and tooling that read, write, render, and convert VRM models — not at end-user avatar galleries. Every entry links to a real repository or official site that has been verified.

## Contents

- [Format & Specification](#format--specification)
- [Core Libraries / SDK](#core-libraries--sdk)
  - [Unity](#unity)
  - [Web / JavaScript](#web--javascript)
  - [Other Engines & Languages](#other-engines--languages)
- [Avatar Creation](#avatar-creation)
- [Converters & Interop](#converters--interop)
- [Inspectors / Viewers / Validators](#inspectors--viewers--validators)
- [Animation & Motion](#animation--motion)
- [VTuber / Application](#vtuber--application)
- [Shaders](#shaders)
- [Tutorials & Docs](#tutorials--docs)
- [Community](#community)
- [Contributing](#contributing)
- [License](#license)

## Format & Specification

- [VRM](https://vrm.dev/en/vrm/) — Open file format for humanoid 3D avatars, built on top of glTF 2.0.
- [vrm-specification](https://github.com/vrm-c/vrm-specification) — Official repository of the VRM format specifications and JSON schemas.
- [VRM 1.0](https://vrm.dev/en/vrm1/) — Documentation for the VRM 1.0 specification and its differences from VRM 0.x.
- [VRM Animation (VRMA)](https://vrm.dev/en/vrma/) — Specification for `.vrma`, a glTF-based animation format that applies to any humanoid VRM model.
- [VRMC_vrm_animation 1.0](https://github.com/vrm-c/vrm-specification/tree/master/specification/VRMC_vrm_animation-1.0) — Specification text and schema for the VRM Animation extension.
- [glTF 2.0](https://github.com/KhronosGroup/glTF) — Khronos runtime 3D asset format that VRM extends; specification, schemas, and extensions.

## Core Libraries / SDK

### Unity

- [UniVRM](https://github.com/vrm-c/UniVRM) — Reference glTF-based VRM implementation for Unity; imports and exports VRM 0.x, VRM 1.0, glTF, and VRMA.

### Web / JavaScript

- [@pixiv/three-vrm](https://github.com/pixiv/three-vrm) — Loads and renders VRM models in Three.js as a GLTFLoader plugin.
- [babylon-vrm-loader](https://github.com/virtual-cast/babylon-vrm-loader) — Loads VRM models in Babylon.js, including humanoid bones, blend shapes, and spring bones.

### Other Engines & Languages

- [godot-vrm](https://github.com/V-Sekai/godot-vrm) — Imports and exports VRM avatars and the MToon shader in Godot Engine (3.2+ and 4.x).
- [VRM Addon for Blender](https://github.com/saturday06/VRM-Addon-for-Blender) — Imports, exports, and edits VRM models in Blender, with humanoid and MToon support.
- [VRM4U](https://github.com/ruyo/VRM4U) — Runtime VRM loader for Unreal Engine 5 that generates bones, blend shapes, spring bones, and humanoid rigs.

## Avatar Creation

- [VRoid Studio](https://vroid.com/en/studio) — Free application from pixiv for modeling humanoid avatars and exporting them as VRM.
- [VRoid Hub](https://hub.vroid.com/en) — Platform for uploading, sharing, and managing VRoid/VRM 3D models, with a public API.

## Converters & Interop

- [VRM Converter for VRChat](https://github.com/esperecyan/VRMConverterForVRChat) — Converts VRM prefabs into VRChat avatars (and back) inside Unity, including mesh merging.

## Inspectors / Viewers / Validators

- [glTF-Validator](https://github.com/KhronosGroup/glTF-Validator) — Validates glTF/GLB assets (the base format of VRM) against the glTF 2.0 specification.
- [three-vrm-viewer](https://github.com/Keshigom/three-vrm-viewer) — Drag-and-drop WebGL preview for VRM models, built on three.js.

<!-- TODO: add a verified metadata/performance inspector here (vrm-inspector slot). -->

## Animation & Motion

- [OpenSeeFace](https://github.com/emilianavt/OpenSeeFace) — Real-time face and facial-landmark tracking library on CPU with Unity integration, used to drive VRM avatars.
- [VMC Protocol](https://protocol.vmc.info/english.html) — OSC-over-UDP protocol for sending motion and expression data between VRM motion-capture applications.

## VTuber / Application

- [VSeeFace](https://www.vseeface.icu/) — Free face- and hand-tracking puppeteering app for VRM avatars, with VMC protocol support.
- [Warudo](https://warudo.app/) — 3D VTubing application supporting VRM models, webcam/ARKit tracking, and full-body motion capture.

## Shaders

- [MToon](https://github.com/Santarh/MToon) — Toon shader for Unity with global illumination support; the standard stylized material used by VRM.
- [babylon-mtoon-material](https://github.com/virtual-cast/babylon-mtoon-material) — WebGL port of the MToon shader for Babylon.js.

## Tutorials & Docs

- [VRM Documentation](https://vrm.dev/en/) — Official documentation covering the VRM format, UniVRM, and avatar development.
- [VRoid Help Center](https://vroid.pixiv.help/hc/en-us) — Official guides and FAQ for VRoid Studio and VRoid Hub.

## Community

- [VRM Consortium](https://vrm-consortium.org/en/) — Non-profit association that develops and promotes the VRM format.

<!-- TODO: add verified official Discord / forum links here. -->

## Contributing

Contributions are welcome! Please open a pull request that follows these rules:

- **Verify first.** Only add a repository or site you have confirmed exists and is reachable. No guessed or remembered URLs.
- **One line, in English, objective.** Describe what the project does in a single concise sentence, without marketing hype.
- **Right section, no duplicates.** Place the entry in the most fitting section and check it is not already listed.
- **Developer value.** The resource should be relevant to VRM/VRoid avatar development (tools, libraries, SDKs, specs, formats).
- **Use canonical URLs.** Link to the GitHub repository or the official site — no shortened or affiliate links.

Use the entry format:

```
- [Project name](URL) — One concise English sentence describing what it does.
```

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
